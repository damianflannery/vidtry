vidtry: This is to playback for DailyBurn video using HLS and Android Media Player (not using VideoView)
=================================

The vidtry application is an experiment in video playback
using MediaPlayer instead of VideoView. It is also
experimenting with touch events (though not gestures just
yet), widgets overlaying a SurfaceView, streaming video
over HTTP, and whatnot.

Usage
-----
Compile and install the application. You will be presented
with a URL history field, where you can enter a URL or pick
from one you have chosen before. Then, click Go, and, if all
goes well, the video will start playing back. You can then
tap on the top half of the screen to enter a different URL
or tap on the bottom half of the screen to bring up a crude
timeline and play/pause button.

Dependencies
------------
None, other than having a source of streaming video that meets
Android's specifications.

Version
-------
This is version 0.1 of this module, meaning it is pretty darn
new. Heck, it's not even commented very much at the moment.

License
-------
The code in this project is licensed under the Apache
Software License 2.0, per the terms of the included LICENSE
file.