# fertitta's CS:GO Config Files

These files are mostly borken up logically to what they controll, making it easy to find and tweak a single setting.

Putting these files on git hub was inspired by https://github.com/samersultan/csgo and samersultan's cfg files were used as a reference

[@johnfertitta](https://twitter.com/johnfertitta)

# Launch options: #

```
-novid -high -threads 6 -nojoy +cl_forcepreload 1 -nod3d9ex
```

# Video settings: #

![Screen shot of video settings](/video_settings.jpg?raw=true)

Video settings are optimzed for visibility, not FPS. I lock my FPS at 160 (monitor hz - 5) and use gsync. To set gysnc up input lag free do the following ([Source](https://www.reddit.com/r/GlobalOffensive/comments/5iv35q/how_to_use_gsync_properly_in_csgo/)):

* Enable G-Sync in the Nvidia Control Panel (obviously)

* In the same Nvidia Control Panel, navigate to 3D-Settings and set V-Sync to ON. You can do this either globally or for CS:GO only (don't be fooled by the common "V-Sync = bad" term. It will only cap the FPS to your monitors max refresh rate, and this will also remove pretty much every microstutter in game!)

* In CS:GO disable V-Sync in the video settings

* Set fps_max 140 (for 144 Hz monitors, if you have 165 Hz, use 160. Just make sure you set the number approx. 4-5 frames lower than your refresh-rate)

# Nade Practice #

The nade practice config is to help use nades, it removes all bots, binds "n" to noclip, binds "p" to give nades. Use by typing "exec nadepractice" into the console
