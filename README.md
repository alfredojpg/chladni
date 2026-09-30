# this is chladni.


chladni is an audio-reactive visualizer that lives inside your daw. it's named after ernst chladni, the german physicist who in the 1780s drew a violin bow across a metal plate dusted with sand. the sand skittered off the parts of the plate that moved and collected along the lines that stayed still, and the patterns changed with the pitch. this plugin is a loose homage to that: sound goes in, and your image gets pushed around by the bass, mids and treble. put it on a track or bus, load an image, and it reacts to whatever passes through. your audio is never touched.


## install

1. download `chladni-setup.exe` and run it
2. rescan plugins in your daw
3. add **chladni** as an effect, click **load image**, and press play

the installer puts the vst3 in the standard folder, offers an optional standalone app, and installs the microsoft webview2 runtime if you don't have it.

**heads up:** the installer isn't code-signed yet, so windows smartscreen may say "unknown publisher". click **more info**, then **run anyway**. if you'd rather check the file first, the sha-256 is:

`960200433FF422DF3BD2D942687AF58C5299898DD2EF3F144C82BF7E32B32898`

## what's in it

- 14 reactive effects driven by bass, mids and treble
- six presets plus an xbox 360 mode
- lfo on any control, and an auto drift mode
- any aspect ratio, including 1:1 for cover art, or type in your own
- record to webm with audio, straight from the plugin (realtime)
- image and settings saved inside your daw project

## known limitations

- windows 10 and 11 (64-bit) only, vst3 only
- recording runs in realtime, so a three minute song takes three minutes
- the recorded audio can drift slightly from the visuals depending on your setup. nudge the **audio sync** slider and record again
- a few hosts handle webgl inside a webview badly. if the window is blank, tell me your daw and version
- pasting and dragging images may be blocked by your daw, so use the **load image** button

## feedback

bugs and feature ideas are welcome. open an issue, or find me on discord (@prodalfredo) or twitter ([@prodalfredo69](https://twitter.com/prodalfredo69)). it helps a lot if you include your daw name and version.

