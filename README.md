
# Camera-Tracker
<p align="center">
	<img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square"/>
</p>
Camera Tracking using the cheapest and the most easiest way to deploy application

The tracking works by dividing the camera by left and right and adding a center area

using media pipe you can narrow down the detection to specify the coordinates of the nose
if the nose is in the area of the center there is no motor movement 
if the nose is detected in the left side of the right side 
the motor will move in the opposite side until it reaches the center area



## Prerequisites
Harware Stuff
- Arduino Uno
- L298N (motor drivers)
- Dc Motor

Python
- Mediapipe
- OpenCV

Camera
- Esp32caM
- Or any Camera


## Installation

Install Mediapipe

```bash
  pip install mediapipe
```
Install OpenCv
```
pip install opencv-python
pip install opencv-contrib-python
```
## Schematic
![alt text](https://hackster.imgix.net/uploads/attachments/1160823/power_2_1_Rj5cILE90T.png?auto=compress%2Cformat&w=680&h=510&fit=max)

## Tech Stack
<img src="https://img.shields.io/badge/Arduino-05122A?style=flat&logo=arduino" alt="arduino Badge" height="25">&nbsp;
<img src="https://img.shields.io/badge/Python-05122A?style=flat&logo=python" alt="python Badge" height="25">&nbsp;

