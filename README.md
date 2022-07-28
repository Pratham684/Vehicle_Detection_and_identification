# VEHICLE DETECTION, TRACKING AND COUNTING
This sample project focuses on "Vechicle Detection, Identification, Counting and Tracking" using [**TensorFlow Object Counting API**]

---

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/36344830-095cc4ec-1431-11e8-8e57-976c40d87cf9.gif">
</p>

---

***The developing is on progress! This sample project will be updated soon, the more talented traffic analyzer app will be available in this repo!***

---

## General Capabilities of This Sample Project

This sample project has more than just counting vehicles, here are the additional capabilities of it:

- Detection and classification of the vehicles (car, truck, bicycle, motorcycle, bus)
- Recognition of approximate vehicle color
- Detection of vehicle direction of travel
- Prediction the speed of the vehicle
- Prediction of approximate vehicle size


## Theory

### System Architecture

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/103478400-80414280-4dd7-11eb-9874-3735359e2c20.png">
</p>

- Vehicle detection and classification have been developed using TensorFlow Object Detection API, [see](https://github.com/ahmetozlu/vehicle_counting_tensorflow/blob/master/vehicle_detection_main.py) for more info.
- Vehicle speed prediction has been developed using OpenCV via image pixel manipulation and calculation, [see](https://github.com/ahmetozlu/vehicle_counting_tensorflow/tree/master/utils/speed_and_direction_prediction_module) for more info.
- Vehicle color prediction has been developed using OpenCV via K-Nearest Neighbors Machine Learning Classification Algorithm is Trained Color Histogram Features, [see](https://github.com/ahmetozlu/vehicle_counting_tensorflow/tree/master/utils/color_recognition_module) for more info.

[TensorFlow™](https://www.tensorflow.org/) is an open source software library for numerical computation using data flow graphs. Nodes in the graph represent mathematical operations, while the graph edges represent the multidimensional data arrays (tensors) communicated between them.

[OpenCV (Open Source Computer Vision Library)](https://opencv.org/about.html) is an open source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products.
