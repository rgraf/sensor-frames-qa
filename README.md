sensor-frames-qa
================

*Quality assurance GUI for frames*

Installation Guide
------------------

### Requirements

To install you need:

* Python 2.7
* OpenCV library 
* Git
* PyScripter editor can support you by project configuration

### Commands

sudo python mask.py 1691.png            // for the test view
sudo python send_frames.py              // to simulate sensor sending frames
sudo rm rec/*.*                         // to clean frames directory

### Live demo

1. clean up 'pic' directory in D:/tmp/final
2. start PyScripter send_frames.py with parameter (in menu) C:\Users\MaxM\Documents\LineSensorRecordings\ D:\tmp\final\pic
3. from command line start: camera_gui.py pic/