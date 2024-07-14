# VEHICLE_MOVEMENT_ANALYSIS_AND_INSIGHT_GENERATION_IN_A_COLLEGE_CAMPUS_USING_EDGE_AI

## Team: VICTUS
#### Team Members :
1. [Abhay Prasad](https://github.com/itsmeabhay01)
2. [Anaswara Biju](https://github.com/anaswarabiju)
3. [Aswathy Satheesh](https://github.com/aaswathi)

#### Project Mentor :
 [Dr. Pradeep C](mailto:jyothish.cg@saintgits.org)
 
 #### College :
 [Saintgits College of Engineering (Autonomous)](https://saintgits.org/saintgits-college-of-engineering/)
## Overview
The project aims to analyze vehicle movements within a college campus, providing valuable insights into parking occupancy, and security. By utilizing advanced object detection and optical character recognition (OCR) techniques, this system can detect vehicles, recognize license plates, and differentiate between authorized and unauthorized vehicles.

## Pre-requisites
- YOLOv8 Framework: For vehicle detection, YOLO (You Only Look Once) framework
- OCR Tools: Optical Character Recognition tools used is EasyOCR for license plate recognition
- Development Environment: Google Colab or a similar environment for model training and experimentation
- Programming Languages: Python for developing and integrating the detection and recognition algorithms
- Vehicle Images: A diverse and comprehensive dataset of vehicle images captured from various angles and lighting conditions

## Category
Machine Learning, Deep Learning

## Semester
6th

## Description
The "Vehicle Movement Analysis and Insight Generation in a College Campus using Edge AI" project seeks to revolutionize how vehicle traffic is managed within a college campus . The system is designed to monitor, analyze, and provide actionable insights into vehicle movements, enhancing campus security, optimizing parking space utilization, and improving overall traffic flow.

## Tools Used

YOLOv8 (You Only Look Once):

Purpose: Object detection framework used to accurately identify and track vehicles  from captured images.

Features: High speed and accuracy, capable of detecting multiple objects in a single frame..

Development Environment: Google Colab

Purpose: Cloud-based platform for developing, training, and testing AI models.

 Features: Access to powerful GPUs, collaborative coding, and ease of use.
 
 Programming Languages:Python

Purpose: Develop and integrate detection and recognition algorithms.

Libraries Used: Tensorflow, pandas

OCR Tools:EasyOCR

Purpose: Optical Character Recognition tools used to read and recognize license plate numbers from detected vehicles.

Features: High accuracy in text recognition, support for various languages and fonts.
     
  
<a id="conclusion"></a>

## Steps to run Code

- Clone the repository
```
!git clone https://github.com/itsmeabhay01/VICTUS.git
```
- Goto the cloned folder.
```
cd /content/VICTUS
```
- Install the dependecies
```
pip install -r requirements.txt

```

- Setting the Directory.
```
cd ultralytics/yolo/v8/detect

```
- Downloading the DeepSORT Files From The Google Drive 
```

https://drive.google.com/drive/folders/1kna8eWGrSfzaR6DtNJ8_GchGgPMv3VC8?usp=sharing
```
- After downloading the DeepSORT Zip file from the drive, unzip it go into the subfolders and place the deep_sort_pytorch folder into the yolo/v8/detect folder

- Downloading a Sample Video from the Google Drive
```
gdown "https://drive.google.com/uc?id=1rjBn8Fl1E_9d0EMVtL24S9aNQOJAveR5&confirm=t"
```

- Run the code with mentioned command below.

- For yolov8 object detection + Tracking
```
python predict.py model=yolov8l.pt source="test3.mp4" show=True
```
- For yolov8 object detection + Tracking + Vehicle Counting
- Download the updated predict.py file from the Google Drive and place it into ultralytics/yolo/v8/detect folder 
- Google Drive Link
```
https://drive.google.com/drive/folders/1awlzTGHBBAn_2pKCkLFADMd1EN_rJETW?usp=sharing
```
- For yolov8 object detection + Tracking + Vehicle Counting
```
python predict.py model=yolov8l.pt source="test3.mp4" show=True
```
## Conclusion

The "Vehicle Movement Analysis and Insight Generation in a College Campus using Edge AI" project demonstrates a significant advancement  to enhance campus security, optimize parking management, and improve overall traffic flow. By integrating advanced object detection and OCR models, the project successfully achieves monitoring and analysis of vehicle movements.



Thank you for your interest in our project!
