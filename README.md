# About SimUI
*SimUI is a theme for [SimpleMenu](https://github.com/fgl82/simplemenu) inspired by [Shaun Inman](https://github.com/shauninman)'s [MinUI](https://github.com/shauninman/MinUI) (a custom launcher for the Trimui Model S, aka PowKiddy A66).*

![Game list](https://user-images.githubusercontent.com/6025373/130760904-96c792f0-b4a1-4a76-9ab5-f11032af69e1.png)
![Add games to favorites](https://user-images.githubusercontent.com/6025373/133490097-227068de-20a9-440a-8c17-fb424e1e1b7c.png)
![Fullscreen thumbnail](https://user-images.githubusercontent.com/6025373/130761069-4f55ee60-3e2e-4ece-b02b-0a144ef1493c.png)
![Fullscreen game list](https://user-images.githubusercontent.com/6025373/130761133-597bd91d-ab92-48c9-80be-975f5dff4b4e.png)
![Favorites logo](https://user-images.githubusercontent.com/6025373/133490185-5e989f0b-f8ab-4e2b-991a-b4e7488cc60d.png)
![Section logo](https://user-images.githubusercontent.com/6025373/130761238-8526b031-2045-4469-b1b5-45c01e286424.png)
![Section group logo](https://user-images.githubusercontent.com/6025373/130761272-cf87323d-992d-4c4f-a1ab-6cb5f4b0ecb9.png)

Having enjoyed [MinUI](https://github.com/shauninman/MinUI)'s intuitive and minimalistic design and [SimpleMenu](https://github.com/fgl82/simplemenu)'s ease of customization, I decided to get acquainted with SimpleMenu's theming engine by recreating MinUI as closely as possible hoping the end product won't be an insult to Shaun's excellent creation 🙂

The goal was to transfer ideas that make MinUI, well, "min" to a more robust platform without sacrificing it's more advanced features. One example of sacrifices that had to be made is the removal of thumbnails from the game list (note: you can still see them in the fullscreen mode), though [they can be turned back on](#thumbnails), but their use is highly discouraged as they don't fit the aesthetic very much, especially on smaller screens.

One other notable example: while SimpleMenu supports multiple controls / key combinations (please read [this wiki page](https://github.com/fgl82/simplemenu/wiki/3.-Controls) to learn more or visit *Settings > Help* in the app) I simply did not find a good place to put hints for all of them so I chose only the essential ones fot the bottom bar.

# Compatibility
The latest release of SimUI is optimised for and has been tested on SimpleMenu version 10.3.1 and should work with all devices that are currently supported by SimpleMenu (original Bittboy, PocketGo and it's clones, devices running RetroFW and OpenDingux). There are two separate versions of the theme directed at different screen resolutions: 320x240 and 640x480. Please use the one corresponding to your device's resolution and put it in the appropriate folder within SimpleMenu. If you encounter any problems on your device, please let me know.

# Installation
1. Download the [latest release](https://github.com/dkodr/SimUI/releases/latest) appropriate for your device's screen resolution
2. Extract it to `/.simplemenu/themes/320x240/` or `/.simplemenu/themes/640x480/` (whichever applies)
3. Choose the theme in SimpleMenu settings

# Thumbnails
Although I would encourage you to keep thumbnails on the game list turned off as it fits the theme's aesthetic much better, they are still supported and can be turned back on. All you have to do is open `theme.ini` and change `show_art = 0` to `show_art = 1`. This setting is independent from the fullscreen mode which is always available.

# Design source files
You can find design source files in [this location](art) and edit them in [Gravit Designer](http://designer.io/) if you ever so desire.

# SimpleMenu button configuration
Right now, in order for SimpleMenu to work properly on Bittboy PocketGo, PowKiddy V90/Q90/Q20 Mini, you have to change the button configuration in `/.simplemenu/config.ini` to this:

```ini
[CONTROLS]
A = 308
B = 306
X = 304
Y = 32
L1 = 9
R1 = 8
UP = 273
DOWN = 274
LEFT = 276
RIGHT = 275
START = 13
SELECT = 27
R = 305
```

Otherwise some keys won't be mapped correctly.
