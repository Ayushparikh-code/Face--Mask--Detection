<h1 align="center">Face Mask Detection</h1>

<div align= "center"><img src="https://github.com/Ayushparikh-code/Face--Mask--Detection/blob/main/download.png?raw=true" width="200" height="200"/>
  <h4>Face Mask Detection system built with OpenCV, Keras/TensorFlow concepts in order to detect face masks in real-time video streams.</h4>
</div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![demo](https://github.com/Ayushparikh-code/Face--Mask--Detection/blob/main/mask-detection-sample.jpg?raw=true)

## :star: Features
The Face mask detector didn't use any morphed masked images dataset. The model is accurate, and since we used the MobileNetV2 architecture, it’s also computationally efficient and thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.

## :file_folder: Dataset
This dataset consists of __3833 images__ belonging to two classes:
*	__with_mask: 1915 images__
*	__without_mask: 1918 images__

The images used were real images of faces wearing masks and not wearing masks. The images were collected from the following sources:
* __Bing & Google Search API__  
* __Kaggle datasets__ 
* __RMFD dataset__  
* __Open-Source Stock Image Websites__  
<div align= "center"><img src="https://github.com/Ayushparikh-code/Face--Mask--Detection/blob/main/face_mask_detection_dataset.jpg?raw=true" /></div>


## :key: Prerequisites

All the dependencies and required libraries are included in the file <code>requirements.txt</code> [See here](https://github.com/Ayushparikh-code/Face--Mask--Detection/blob/main/requirements.txt)

## 🚀&nbsp; Installation
1. Clone the repo
```
$ git clone https://github.com/Ayushparikh-code/Face--Mask--Detection.git
```

2. Change your directory to the cloned repo 
```
$ cd Face--Mask--Detection
```

3. Now, run the following command in your Terminal/Command Prompt to install the libraries required
```
$ pip install -r requirements.txt
```
## :bulb: Working

<p align="centre">
  <img src="https://github.com/Ayushparikh-code/Face--Mask--Detection/blob/main/face_mask_detection_phases.png?raw=true">
  
  
1. Open terminal. Go into the cloned project directory and type the following command:
```
$ python train_mask_detector.py  
```

2. To detect face masks in real-time video streams type the following command:
```
$ python detect_mask_video.py 
```
## :key: Results

#### This model gave 98% accuracy for Face Mask Detection after training via <code>tensorflow>=1.15.2</code>

#### Here is the following accuracy/loss training curve plot
![](https://github.com/Ayushparikh-code/Face--Mask--Detection/blob/main/plot.png?raw=true)

#### IMAGES
<p align="left">
  <img src="https://github.com/Ayushparikh-code/Face--Mask--Detection/blob/main/face-mask-detection1.jpg?raw=true" width=400 height=340>
  <img src="https://github.com/Ayushparikh-code/Face--Mask--Detection/blob/main/result3.jpg?raw=true" height=340/>


Note: If you Like this project then just follow me👍 and Star✨ this repository !
