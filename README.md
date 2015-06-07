morse-player
============

Morse code translator with playback included. Part of [/g/'s Programming Projects for n00bz](https://github.com/keplr/programming-projects-for-n00bz). If you aren't familiar with Morse Code, see [this article on Wikipedia](http://en.wikipedia.org/wiki/Morse_code).

Dependencies
-------------

python2.7, pyaudio

Usage
-----

1. Open a Terminal window and go to the repository folder. Maybe you'll need to change permissions to the executable file (`$ chmod a+x morse-player`).
2. Run it via `./morse-code` and then type whatever you want!
<br>
<img src="https://raw.githubusercontent.com/queq/morse-player/master/screenshots/dbe4.png"/>

Issues
------

* While on playback, multiple warnings appear on Terminal (ALSA related), so you'll need to scroll up to see the translated dots and dashes.

TODO
----

* Wrap this up nice and cute in a GUI, in order to avoid the previous issue
* Allow translation in both ways
* Allow user to change certain parameters, such as tone frequency, duration and amplitude on the fly.
