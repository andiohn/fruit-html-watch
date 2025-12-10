# fruit-html-watch
HTML Watch recreation of a fruit smartwatch, WITH burn in prevention. 

This is a recreation of a certain companies' smart watch but with some fun additions.

1. Liquid Glass background
2. Can use any image URL as the background by passing in a url flag, along with tile, cover and center modes
3. A second image can be chosen too, to help with burn in prevention. Just pass the same flags but with a 2 at the end.
4. Can use any colour as a background instead of an image, turned on with a URL flag too
5. Date can be turned on with a URL flag too
6. Hours of automatic reload are added with a flag.

<img width="1920" height="993" alt="image" src="https://github.com/user-attachments/assets/b0c3e132-2d14-4df5-b092-57118806bbf8" />


URL Flags

|Flag|Value|Description|Default|
|-|-|-|-|
|?bg_img=|[URL]|Full URL of a background image (e.g., .jpg, .png).|None|(Solid Color)|
|?bg_mode=|tile, center, cover|How the background image is displayed.|center|
|?bg_img2=|[URL]|Full URL of a second background image (e.g., .jpg, .png).|None|(Solid Color)|
|?bg_mode2=|tile, center, cover|How the second background image is displayed.|center|
|?bg=|[HEX or Color Name]|Sets the color of the translucent "Liquid Glass" clock face.|#000000 (Black)|
|?date=|show or hide|Toggles the visibility of the date and day of the week.|hide|
|?reload_h=|# of Hours|Set the interval of an automagic reload, without cache|12 hours|
|?clock_bg_img=|[URL]|Set unblurred clock background|None (try https://gifroz.vercel.app)
|?clock_bg_mode=|tile, center, cover|How the clock background image is displayed.|center|

EXAMPLES(Preview):

|Descriptions|Link|
|-|-|
|**MULTI** - Using 2 randoms (on each load!) from https://picsum.photos/ date on, 1 hour reload, cover image|https://htmlpreview.github.io/?https://github.com/andiohn/fruit-html-watch/blob/main/7th-configure-reload.html&bg_img=https://picsum.photos/1920/1080?random=1&bg_mode=cover&bg_img2=https://picsum.photos/1920/1080?random=2&bg_mode2=cover&date=show&reload_h=1|
|**MULTI** - Example 1 and Grey Linen, date on, reload 2 hour, cover image|https://htmlpreview.github.io/?https://github.com/andiohn/fruit-html-watch/blob/main/7th-configure-reload.html&bg_img=https://images.pexels.com/photos/11177799/pexels-photo-11177799.jpeg&bg_mode=cover&bg_img2=https://cdn.osxdaily.com/wp-content/uploads/2011/10/NSTexturedFullScreenBackgroundColor.png&bg_mode2=tile&date=show&reload_h=2|
|1 Hour Reload Random image from imageipsum.com, 1920x1080,cover,date on|https://htmlpreview.github.io/?https://github.com/andiohn/fruit-html-watch/blob/main/7th-configure-reload.html&bg_img=http://imageipsum.com/1920x1080&bg_mode=cover&date=show&reload_h=1|
|1 Hour RANDOM gif from Onyx-Nostalgia/gifroz, 1920x1080,center,date on|https://htmlpreview.github.io/?https://github.com/andiohn/fruit-html-watch/blob/main/7th-configure-reload.html&bg_img=https://gifroz.vercel.app&bg_mode=center&date=show&reload_h=1|
|**MULTI** - Example 1 and Grey Linen, gif clock background, date on, reload 2 hour, cover image|https://htmlpreview.github.io/?https://github.com/andiohn/fruit-html-watch/blob/main/10th-clockblur.html&bg_img=https://picsum.photos/1920/1080?random=1&bg_mode=cover&bg_img2=https://picsum.photos/1920/1080?random=2&bg_mode2=cover&date=show&reload_h=1&clock_bg_img=https://gifroz.vercel.app&blur=15&clock_bg_mode=tile|
|Awesome Mac OS default wallpaper, date on, cover image|https://htmlpreview.github.io/?https://github.com/andiohn/fruit-html-watch/blob/main/7th-configure-reload.html&bg_img=https://images.pexels.com/photos/11177799/pexels-photo-11177799.jpeg&bg_mode=cover&date=show|
|iPad iOS 13 Image background, date on, center image|https://htmlpreview.github.io/?https://github.com/andiohn/fruit-html-watch/blob/main/7th-configure-reload.html&bg_img=https://wallpapers.ispazio.net/wp-content/uploads/2021/06/ispazio-13.jpg&bg_mode=center&date=show|
|Mac OS Sequoia (Large) background, date on, cover image|https://htmlpreview.github.io/?https://github.com/andiohn/fruit-html-watch/blob/main/7th-configure-reload.html&bg_img=https://wallpapers.ispazio.net/wp-content/uploads/2024/06/SequoiaLight.png&bg_mode=cover&date=show|
|Classic Mac OS Grey Linen background, date off|https://htmlpreview.github.io/?https://github.com/andiohn/fruit-html-watch/blob/main/7th-configure-reload.html&bg_img=https://cdn.osxdaily.com/wp-content/uploads/2011/10/NSTexturedFullScreenBackgroundColor.png&bg_mode=tile&date=hide|
|iPhone Background, date on, tile image|https://htmlpreview.github.io/?https://github.com/andiohn/fruit-html-watch/blob/main/7th-configure-reload.html&bg_img=https://wallpapers.ispazio.net/wp-content/uploads/2021/06/ios-15-stock-wallapper-from-ispazio-dark.png&bg_mode=tile&date=show|
