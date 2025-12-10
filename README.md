# fruit-html-watch
HTML Watch recreation of a fruit smartwatch

This is a recreation of a certain companies' smart watch but with some fun additions.

1. Liquid Glass background
2. Can use any image URL as the background by passing in a url flag, along with tile, cover and center modes
3. Can use any colour as a background instead of an image, turned on with a URL flag too
4. Date can be turned on with a URL flag too

URL Flags

|Flag|Value|Description|Default|
|-|-|-|-|
|?bg_img=|[URL]|Full URL of a background image (e.g., .jpg, .png).|None|(Solid Color)|
|?bg_mode=|tile, center, cover|How the background image is displayed.|center|
|?bg=|[HEX or Color Name]|Sets the color of the translucent "Liquid Glass" clock face.|#000000 (Black)|
|?date=|show or hide|Toggles the visibility of the date and day of the week.|hide|

EXAMPLE (Preview):
https://htmlpreview.github.io/?https://github.com/andiohn/fruit-html-watch/blob/main/5th-rev-add-date.html&bg_img=https://images.pexels.com/photos/11177799/pexels-photo-11177799.jpeg&bg_mode=cover&date=show
