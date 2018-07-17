# `/filter` Filters
All endpoints below require the `image.filter` permission and use the following body object:

| Property name | Type   | Description |
|---------------|--------|-------------|
| picture       | String | URL of the picture you want to reference |


<h6 class="endpoint post"></h6>
## /blurple
<img src="./images/preview/blurple.png" class="preview-img">

|             |                         |
|-------------|-------------------------|
| Render Time | Average (3-5s)          |
| Permission  | image.gen.light.blurple |

<br>
<br>

<h6 class="endpoint post"></h6>
## /deepfry
<img src="./images/preview/deepfry.png" class="preview-img">

|             |                         |
|-------------|-------------------------|
| Render Time | Terrible (> 12s)        |
| Permission  | image.gen.light.deepfry |

<br>
<br>

<h6 class="endpoint post"></h6>
## /distort
<img src="./images/preview/distort.png" class="preview-img">

|             |                         |
|-------------|-------------------------|
| Render Time | Terrible (> 12s)        |
| Permission  | image.gen.heavy.distort |

The distort endpoint can use special arguments to mold the picture into whatever you like.
All arguments in the next table are optional.


| Property name  | Type    | Description |
|----------------|---------|-------------|
| saturate       | Boolean | Saturate or desaturates the image, do not define to not use the filter |
| saturateAmount | Number  | The amount to saturate or desaturate the image (Must be between 0 and 80) |
| spin           | Number  | The amount of hue spin to apply to the image (Must be between 0 and 359) |
| implode        | Number  | The amount of implosion to apply to the image (Must be between 0 and 10) |
| roll           | Boolean | Whether or not to roll the image (This enables `verticalRoll` and `horizontalRoll`) |
| verticalRoll   | Boolean | The amount of roll to be applied verically (Must be between -180 and 180) |
| horizontalRoll | Boolean | The amount of roll to be applied horizontally (Must be between -180 and 180) |
| swirl          | Boolean | The amount of swirl to apply (Must be between -180 and 180) |

<br>
<br>

<h6 class="endpoint post"></h6>
## /grayscale
<img src="./images/preview/grayscale.png" class="preview-img">

|             |                           |
|-------------|---------------------------|
| Render Time | Fast (< 1.5s)             |
| Permission  | image.gen.light.grayscale |

<br>
<br>

<h6 class="endpoint post"></h6>
## /icey
<img src="./images/preview/icey.png" class="preview-img">

|             |                         |
|-------------|-------------------------|
| Render Time | Okay (~2s)              |
| Permission  | image.gen.light.icey    |

<br>
<br>

<h6 class="endpoint post"></h6>
## /magik
<img src="./images/preview/magik.png" class="preview-img">

|             |                         |
|-------------|-------------------------|
| Render Time | Terrible (> 12s)        |
| Permission  | image.gen.heavy.magik   |

<br>
<br>

<h6 class="endpoint post"></h6>
## /sepia
<img src="./images/preview/sepia.png" class="preview-img">

|             |                         |
|-------------|-------------------------|
| Render Time | Okay (~2s)              |
| Permission  | image.gen.light.sepia   |

<br>
<br>

<h6 class="endpoint post"></h6>
## /sharpen
<img src="./images/preview/sharpen.png" class="preview-img">

|             |                         |
|-------------|-------------------------|
| Render Time | Average (3-5s)          |
| Permission  | image.gen.light.sharpen |

<br>
<br>