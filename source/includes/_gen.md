# `/gen` Image Generation

All endpoints below require the `image.gen` permission.

<h6 class="endpoint post"></h6>
## /animeprotest
<img src="./images/preview/animeprotest.png" class="preview-img">

|             |                              |
|-------------|------------------------------|
| Render Time | Fast (< 1.5s)                |
| Permission  | image.gen.light.animeprotest |
| Dimensions  | 219 x 300                    |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| text          | String | text you want to use in the picture (< 100 length) |

<h6 class="endpoint post"></h6>
## /art
<img src="./images/preview/art.png" class="preview-img">

|             |                     |
|-------------|---------------------|
| Render Time | Okay (~2s)          |
| Permission  | image.gen.light.art |
| Dimensions  | 1364 x 1534         |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| picture       | String | url you want to use in the picture |

<h6 class="endpoint post"></h6>
## /changemymind
<img src="./images/preview/changemymind.png" class="preview-img long">

|             |                              |
|-------------|------------------------------|
| Render Time | Fast (< 1.5s)                |
| Permission  | image.gen.light.changemymind |
| Dimensions  | 800 x 450                    |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| text          | String | text you want to use in the picture (< 100 length) |

<h6 class="endpoint post"></h6>
## /dogbite
<img src="./images/preview/dogbite.png" class="preview-img">

|             |                         |
|-------------|-------------------------|
| Render Time | Fast (< 1.5s)           |
| Permission  | image.gen.light.dogbite |
| Dimensions  | 500 x 491               |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| text          | String | text you want to use in the picture (< 30 length) |

<h6 class="endpoint post"></h6>
## /durv
<img src="./images/preview/durv.png" class="preview-img long">

|             |                      |
|-------------|----------------------|
| Render Time | Fast (< 1.5s)        |
| Permission  | image.gen.light.durv |
| Dimensions  | 401 x 226            |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| picture       | String | url you want to use in the picture |

<h6 class="endpoint post"></h6>
## /eliminated
<img src="./images/preview/eliminated.png" class="preview-img">

|             |                            |
|-------------|----------------------------|
| Render Time | Average (3-5s)             |
| Permission  | image.gen.light.eliminated |
| Dimensions  | > 381 x 70                 |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| text          | String | text you want to use in the picture (< 30 length) |