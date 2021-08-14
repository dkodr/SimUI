# About SimUI
*SimUI is a theme for [SimpleMenu](https://github.com/fgl82/simplemenu) inspired by [Shaun Inman](https://github.com/shauninman)'s [MinUI](https://github.com/shauninman/MinUI) (a custom launcher for the Trimui Model S, aka PowKiddy A66).*

![Screenshot1](https://user-images.githubusercontent.com/6025373/129362366-40c913d5-e0f9-49bf-b3da-700c4e6629c6.png)
![Screenshot2](https://user-images.githubusercontent.com/6025373/129362371-e078166d-bcc1-43fa-b2f8-4bfc9bbb1ace.png)
![Screenshot3](https://user-images.githubusercontent.com/6025373/129362373-2cea8d41-87aa-49e1-8317-1281fe556a41.png)

Having enjoyed [MinUI](https://github.com/shauninman/MinUI)'s intuitive and minimalistic design and [SimpleMenu](https://github.com/fgl82/simplemenu)'s ease of customization, I decided to get acquainted with SimpleMenu's theming engine by recreating MinUI as closely as possible hoping the end product won't be an insult to Shaun's excellent creation 🙂

The goal was to transfer ideas that make MinUI, well, "min" to a more robust platform without sacrificing it's more advanced features. One example of sacrifices that had to be made is the reduction of media thumbnails' size and while SimUI still supports them, their use is highly discouraged as they don't fit the aesthetic very much (especially on smaller screens).

One other notable example: while SimpleMenu supports multiple controls / key combinations (please read [this wiki page](https://github.com/fgl82/simplemenu/wiki/3.-Controls) to learn more) I simply did not find a good place to put hints for all of them so I chose only the essential ones fot the bottom bar.

# Compatibility
SimUI should work with all devices that are currently supported by SimpleMenu. For now, only a 320x240 version has been created but I'm also planning to release 480x320 and 640x480 variants. If you encounter any problems on your device, please let me know. The theme has been tested and confirmed to be working correctly on these devices: PowKiddy Q20 Mini.

# Installation
1. Download the [latest release](https://github.com/dkodr/SimUI/releases/latest)
2. Extract it to `/.simplemenu/themes/320x240/`
3. Choose the theme in SimpleMenu settings

# SimpleMenu button configuration
Right now, in order for SimpleMenu to work properly on Bittboy PocketGO, PowKiddy V90/Q90/Q20 Mini, you have to change the button configuration in `/.simplemenu/config.ini` to this:

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

# Roadmap
- [X] 320x240 version
- [ ] 480x320 version
- [ ] 640x480 version
