# Measuring the distance to the nearest vehicle
For developing advanced driving assistance systems (ADAS) it is required to detect the distance to the nearest vehicle from the user vehicle using the vehicle mounted camera. This repository contains the code for estimating the distance to the nearest vehicle using the the principle of similar triangles. For detecting objects Yolo v3 has been used.

![ezgif com-gif-maker (3)](https://user-images.githubusercontent.com/40798690/87365452-e42b3280-c53b-11ea-85ed-0bf9615ac5b3.gif)

For object detection Yolo v3 has been used. The code for Yolo V3 has been taken from https://github.com/qqwweee/keras-yolo3. Then detection file has been modified to get the nearest vehicle and to get the perspective distance to that vehicle using the principle of similar triangles.


## Getting Started
* Install the required dependencies: (for reference see https://github.com/qqwweee/keras-yolo3 )
* download the pre-trained weight from: [download](https://drive.google.com/file/d/1BEfbOIdso_rVsQH8Tq_V-b1Kbt1bNK3S/view?usp=sharing)
* [yolo.py](https://github.com/monjurulkarim/vehicle_distance/blob/master/yolo.py) : this file is for the detecting objects. Function detect_image has been modified to calculate the distance to the nearest car.
* [yolo_video.py](https://github.com/monjurulkarim/vehicle_distance/blob/master/yolo_video.py): call this code to run the inference

