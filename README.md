# FYP_Remote_Access_Camera_HUD

Final year Project - 2023

## Materials:
1. Raspberry Pi 4B 4GB RAM
2. IP Camera
3. 1.44 Inch LCD Display
4. 3D Printed Attachement Casings


## Concept:
1. Imagine FPV (First Person View) Drones. You wear a VR-Headset-Like Headgear. You will see whatever the drone see. But cant see your surrounding.
2. Imagine current mobile robots usage in Military and SAR. The mobile robots are used to scout operation area for hazards and further planning. Whatever the robot see, will be displayed on ONE SCREEN DISPLAY ONLY.
3. Imagine a security guard, communicating to a Control Room that can view CCTVs. Whatever the CCTVs see, ONLY the person in the Control Room can see the video feed.

Now what if a person can see whatever a robot see, enhanced with image processing, while still being able to see their surrounding? What if every operation member in Military or SAR can see whatever the mobile robot sees during an operation? What if a security guard can see a CCTV feed of another angle, while being able to see his surrounding too? Its like have additional eye right?

## Method:
- 1.44 Inch LCD Display attached to glasess or headgear.
- Access IP Camera or any video stream feed remotely using OpenCV.
- The video feed will be displayed on the 1.44 Inch LCD.
- Added image processing to recognize hazards and humans


## Reference

1- Youtube Livestream, using pafy (python3.9 -m pip install pafy)
- https://stackoverflow.com/questions/43032163/how-to-read-youtube-live-stream-using-opencv-python
- https://stackoverflow.com/questions/73256287/i-want-to-process-a-live-stream-from-youtube-with-opencv

2- pafy docs
- https://pypi.org/project/pafy/

3- youtub_dl error
- https://stackoverflow.com/questions/44348032/importerror-no-module-named-youtube-dl

4- 1.44 Inch LCD Display Wiki. Setups and Drivers Installation
- https://www.waveshare.com/wiki/1.44inch_LCD_HAT
