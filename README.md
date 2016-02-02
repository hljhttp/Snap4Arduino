Snap4Arduino
============

![Snap4Arduino Logo](http://s4a.cat/snap/img/logo-top.png)

Snap4Arduino binds Snap! and Arduino together in a desktop application for GNU/Linux, MacOSX and MS Windows.

Please check out our official website for further info:

[s4a.cat/snap](http://s4a.cat/snap)

Acknowledgements
================

Of course, this project wouldn't exist without:

* [Snap!](http://snap.berkeley.edu)
* [Arduino](http://arduino.cc)
* [Node-Webkit](https://github.com/rogerwang/node-webkit)



![Edutec Logo](http://edutec.citilab.eu/img/logo.gif)
![Citilab Logo](http://s4a.cat/img/citilab.png)

Packager Scripts
================
The Snap4Arduino packager is not included in this repository because it contains lots of binaries, which would increase its size way too much.

The packager, including all binaries and builder scripts, can be found [here](http://vps34736.ovh.net/snap4arduino/Snap4Arduino-builder.tar.gz), while the _nwjs_ source and binaries can be found [here](https://github.com/nwjs/nw.js).

The packager includes the following scripts:

* **update.sh** → Updates the packager to the latest Snap4Arduino version available in this repository
* **build-gnu32.sh** → Builds the GNU/Linux 32b package based on the Snap4Arduino version in the packager
* **build-gnu64.sh** → Builds the GNU/Linux 64b package based on the Snap4Arduino version in the packager
* **build-osx.sh** → Builds the MacOSX package based on the Snap4Arduino version in the packager
* **build-win32.sh** → Builds the Microsoft Windows package based on the Snap4Arduino version in the packager
* **update-build-all.sh** → Updates the packager to the latest Snap4Arduino version available in this repository and builds packages for all platforms. Additionally, it copies these ready-to-download packages into _/var/www/snap4arduino_, which should exist.

The Microsoft Windows packaging script depends on [Inno Setup](http://www.jrsoftware.org/isinfo.php), ran headless by Wine.

Old Repository
==============

This repository contains only source files. The old, huge (2Gb+!) repository that contained all binaries can still be find for archaeologic purposes at: https://github.com/edutec/Snap4Arduino-old-huge
