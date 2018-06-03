# decastreamer
Web app for streaming visualization of Deca tag devices

## Installation

python -m pip install --upgrade pip

Python 3 required. Modules needed:
- pillow
- appjar
- matplotlib
- serial

http://appjar.info/pythonBasics/


## Usage

Usually you have to open a putty window to the tag and then start reading data with "lep". Then close putty and run the app.
When the app starts, to start pulling data, press the "Start Reading" button in te upper left hand corner.
If you wish to change the location of anchors, those are set in the AccessibleName property of the pictureboxes. 
To change the port name/id, look in Form1.cs around line 89.

New serial: POS,1,<name>,x,y,z,<confidence>,hex value


```

## Inputs

tom

## Advanced Configuration


## API


## Configuration



## Development


## Copyright

Copyright (c) 2017 Cardinal Peak
