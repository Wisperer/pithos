Pithosfly
------

A fork for Pithos, a native Pandora Radio client for Linux, that saves the stream you are listening to disk.
It splits and saves music intelligently into mp3 files.

Configure folder to save to by adding the following to pithos.ini (usually found in ~/.config/):
`save_to=/path/to/folder`

Run:
`python3 -m pithos`
Or build and install per Pithos' instructions:
* Remove if already installed installed
* Then run
`sudo apt-get install python3-setuptools python3-dbus python3-gi python3-gi-cairo \
  gir1.2-gstreamer-1.0 gir1.2-gst-plugins-base-1.0 gstreamer1.0-plugins-good gstreamer1.0-plugins-bad  \
  python3-pylast gir1.2-appindicator3-0.1 gir1.2-notify-0.7 gir1.2-keybinder-3.0 gnome-icon-theme-symbolic
sudo ./setup.py install
`
(you might need some more libs for the latest pithos)
More details [here](https://github.com/pithos/pithos/wiki/Installing-from-Source)

The original Pithos [homepage is here](http://pithos.github.io).

License: GNU GPLv3
