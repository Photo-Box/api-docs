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
| picture       | String | url you want to use in the picture (< 100 length) |

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
| text          | String | text you want to use in the picture |