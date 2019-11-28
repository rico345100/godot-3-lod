# LOD(Level Of Detail) Script for Godot 3.1.1
Simple LOD script for Godot 3.1.1.

## How to use?
First you need a object that has 3 lod mesh as child, each must be named "LOD0", "LOD1", "LOD2".

Import your LOD mesh and attach LevelOfDetail.gd script into parent.

If there is a camera in your scene named "Camera", auto detect camera option will find it automatically.

But there is no camera named "Camera", you can just turn off auto detect camera and assign camera directly.

Adjust values in LOD Distance 0 ~ 2. LOD culling option will decide to render object if its further than LOD2 distance, and it's true by default.

Tweak the values until fine distance of each LOD work. That's it!

## What? No, just show me how!!
Alright, here's the [link for video](https://youtu.be/cy2eNuo2tCM).


## License
MIT. Free to use.

## Buy me a coffee!
Donations are big help for me to continue my development!

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=PVXTU5FJNBLDS)