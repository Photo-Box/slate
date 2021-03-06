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
| text          | String | text you want to use in the picture (max length is 100) |

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
| picture       | String | URL of the picture you want to reference |

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
| text          | String | text you want to use in the picture (max length is 100) |

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
| text          | String | text you want to use in the picture (max length is 30) |

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
| picture       | String | URL of the picture you want to reference |

<h6 class="endpoint post"></h6>
## /eliminated
<img src="./images/preview/eliminated.png" class="preview-img">

|             |                             |
|-------------|-----------------------------|
| Render Time | Average (3-5s)              |
| Permission  | image.gen.medium.eliminated |
| Dimensions  | > 381 x 70                  |

### Body Object

| Property name | Type    | Description |
|---------------|---------|-------------|
| text          | String  | text you want to use in the picture (max length is 30) |
| fire          | Number? | number next to the fire symbol (defaults to a number between 60-100) |

<h6 class="endpoint post"></h6>
## /firstwords
<img src="./images/preview/firstwords.png" class="preview-img">

|             |                            |
|-------------|----------------------------|
| Render Time | Fast (< 1.5s)              |
| Permission  | image.gen.light.firstwords |
| Dimensions  | 1024 x 1069                |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| text          | String | text you want to use in the picture (max length is 100) |

<h6 class="endpoint post"></h6>
## /nickelback
<img src="./images/preview/nickelback.png" class="preview-img long">

|             |                            |
|-------------|----------------------------|
| Render Time | Okay (~2s)                 |
| Permission  | image.gen.light.nickelback |
| Dimensions  | 1024 x 576                 |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| picture       | String | URL of the picture you want to reference |

<h6 class="endpoint post"></h6>
## /nutbutton
<img src="./images/preview/nutbutton.png" class="preview-img">

|             |                           |
|-------------|---------------------------|
| Render Time | Okay (~2s)                |
| Permission  | image.gen.light.nutbutton |
| Dimensions  | 600 x 446                 |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| text          | String | text you want to use in the picture (max length is 30) |

<h6 class="endpoint post"></h6>
## /okbyemom
<img src="./images/preview/okbyemom.png" class="preview-img">

|             |                          |
|-------------|--------------------------|
| Render Time | Fast (< 1.5s)            |
| Permission  | image.gen.light.okbyemom |
| Dimensions  | 600 x 600                |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| text          | String | text you want to use in the picture (max length is 30) |

<h6 class="endpoint post"></h6>
## /pornhub
<img src="./images/preview/pornhub.png" class="preview-img long">

|             |                         |
|-------------|-------------------------|
| Render Time | Okay (~2s)              |
| Permission  | image.gen.light.pornhub |
| Dimensions  | 805 x 628               |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| picture       | String | URL of the picture you want to reference |
| title         | String | title of the video (max length is 30) |

<h6 class="endpoint post"></h6>
## /respects
<img src="./images/preview/respects.png" class="preview-img long">

|             |                          |
|-------------|--------------------------|
| Render Time | Fast (< 1.5s)            |
| Permission  | image.gen.light.respects |
| Dimensions  | 960 x 540                |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| picture       | String | URL of the picture you want to reference |

<h6 class="endpoint post"></h6>
## /starvstheforcesof
<img src="./images/preview/starvstheforcesof.png" class="preview-img long">

|             |                                    |
|-------------|------------------------------------|
| Render Time | Slow (6-12s)                       |
| Permission  | image.gen.medium.starvstheforcesof |
| Dimensions  | 1920 x 1080                        |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| picture       | String | URL of the picture you want to reference |

<h6 class="endpoint post"></h6>
## /tinder
<img src="./images/preview/tinder.png" class="preview-img">

|             |                        |
|-------------|------------------------|
| Render Time | Fast (< 1.5s)          |
| Permission  | image.gen.light.tinder |
| Dimensions  | 570 x 738              |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| pictureOne    | String | URL of the first picture want to reference |
| pictureTwo    | String | UL of the second picture want to reference |

<h6 class="endpoint post"></h6>
## /ttt
<img src="./images/preview/ttt.png" class="preview-img long">

|             |                     |
|-------------|---------------------|
| Render Time | Fast (< 1.5s)       |
| Permission  | image.gen.light.ttt |
| Dimensions  | 421 x 269           |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| title         | String | name to use in the title of the window (max length is 30) |
| avatar        | String | url of the avatar |
| text          | String | text to use as content of the window (max length is 150) |

<h6 class="endpoint post"></h6>
## /waifu
<img src="./images/preview/waifu.png" class="preview-img long">

|             |                       |
|-------------|-----------------------|
| Render Time | Fast (< 1.5s)         |
| Permission  | image.gen.light.waifu |
| Dimensions  | 450 x 340             |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| picture       | String | URL of the picture you want to reference |

<h6 class="endpoint post"></h6>
## /wanted
<img src="./images/preview/wanted.png" class="preview-img">

|             |                         |
|-------------|-------------------------|
| Render Time | Slow (6-12s)            |
| Permission  | image.gen.medium.wanted |
| Dimensions  | 889 x 1200              |

### Body Object

| Property name | Type   | Description |
|---------------|--------|-------------|
| picture       | String | URL of the picture you want to reference |
| title         | String | name to use in the poster (max length is 30) |