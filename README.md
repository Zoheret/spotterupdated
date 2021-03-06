Spotter v1.1 : LED based real-time video tracking for behavioural experiments developed by Nora Gaspar

===============================

[Spotter version 1.1](https://github.com/gasparnori/spotterupdated) can track LEDs in real-time video stream--either from a webcam, video file--and simultaneously write encoded video to disk, while outputs the tracked variables as analog and digital signals. It is based on the [OpenCV](http://opencv.org/) library and interfaces with Arduino Mega


Spotter v1.0 developed by Ronny Eichler is available [here] (https://github.com/wonkoderverstaendige)



For more detailed documentation, please refer to: [full documentation](docs/full_documentation_v1.1.pdf).

Requirements
------------

Tested on Windows 7

- Python 2.7 (Python 3.x is not supported)
- numpy 1.6+
- OpenCV 2.4+
- pyOpenGL
- pyQt4
- pySerial

- Arduino Mega

**Windows**

The simplest, but not very lightweight method for installing all
requirements is to download the [PythonXY](http://code.google.com/p/pythonxy/wiki/Downloads)
distribution and perform a  "full" installation. Alternatively, a custom
installation is enough if all required packages are selected.

TODO: The opencv package distributed in python XY can not decode most videos. Install without,
and grab from e.g. grohlke (see below).

_Bare install:_
Download and install Python 2.7 32bit

Add python to the PATH variable by appending 

    ;C:\Python27\;C:\Python27\Scripts

under MyComputer->Properties->Advanced->Env Variables->Path
    
Install required packages by downlaoding and innstalling following binaries
(choose win32-py2.7 links) in order:

    http://www.lfd.uci.edu/~gohlke/pythonlibs/#pip
    http://www.lfd.uci.edu/~gohlke/pythonlibs/#numpy
    http://www.lfd.uci.edu/~gohlke/pythonlibs/#pyqt
    http://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv
    http://www.lfd.uci.edu/~gohlke/pythonlibs/#pyopengl
    http://www.lfd.uci.edu/~gohlke/pythonlibs/#pyserial

**MaxOSX**
*Stand by.*
*Install XCode, install MacPorts. Install py27- packages.*

**LINUX**

    apt-get install the following packages:
    (among others...)
    python-numpy
    python-scipy
    python-qt4-gl

Installation
------------

**With git**

    git clone https://github.com/gasparnori/spotterupdated.git

**Without git**

Download and extract the zip file
