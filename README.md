# fertitta's CS:GO Config Files

These files are mostly borken up logically to what they controll, making it easy to find and tweak a single setting.

Putting these files on git hub was inspired by https://github.com/samersultan/csgo and samersultan's cfg files were used as a reference

[@johnfertitta](https://twitter.com/johnfertitta)

# Launch options: #

```
-novid -nojoy +cl_forcepreload 1 -nod3d9ex -freq 165 +mat_queue_mode 2
```

# Video settings: #

![Screen shot of video settings](/video_settings.jpg?raw=true)

Video settings are optimzed for visibility, not FPS. I lock my FPS at 162 (monitor hz - 3) and use gsync. To set gysnc up input lag free do the following ([Source](https://www.reddit.com/r/nvidia/comments/5e40o3/nvidia_gsync_lag_analysis_tldw_no_additional/)):

* Enable G-Sync in the Nvidia Control Panel (obviously)

* In the same Nvidia Control Panel, navigate to 3D-Settings and set V-Sync to ON. You can do this either globally or for CS:GO only (don't be fooled by the common "V-Sync = bad" term. It will only cap the FPS to your monitors max refresh rate, and this will also remove pretty much every microstutter in game!)

* In CS:GO disable V-Sync in the video settings

* Set fps_max 142 (for 144 Hz monitors, if you have 165 Hz, use 162. Just make sure you set the number approx. 3-5 frames lower than your refresh-rate)

Additionally I use [VibranceGui](https://vibrancegui.com/) to automatically set my vibrance level in nVida countrol panel to 75%

# Nade Practice #

The nade practice config is to help use nades, it removes all bots, binds "n" to noclip, binds "p" to give nades. Use by typing "exec nadepractice" into the console

# Specs #

* AMD - Ryzen 7 1700 @ 3.75 ghz
* EVGA - GeForce GTX 1080 Ti 11GB SC2 Video Card
* ASUS - Crosshair VI Hero WIFI
* G.Skill - Ripjaws V Series 16GB (2 x 8GB) DDR4-3200 Memory @ 3200 mhz
* Samsung - 960 EVO 250GB M.2-2280 Solid State Drive
* Samsung - 850 EVO-Series 500GB 2.5" Solid State Drive
* Corsair - RM 750W 80+ Gold Certified Fully-Modular ATX Power Supply
* Asus - PG279Q ROG Swift 27.0" 2560x1440 165Hz Monitor
* Razer - BlackWidow Tournament Edition Chroma Wired Gaming Keyboard
* SteelSeries - Rival 300 Wired Optical Mouse
* Schiit - Modi 2 External DAC
* Schiit - Magni 2 Amplifier
* Sennheiser - HD6XX Headphones
* Blue - Yeti Black Microphone
* Logitech - G840 Mousepad
