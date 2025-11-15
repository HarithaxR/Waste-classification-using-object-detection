# Waste Classification Using Object Detection

This repository contains the files and instructions for my project on waste classification using object detection.

**Languages & Tools Used:**
- **Programming Language:** Python
- **Front-end:** HTML, CSS, JavaScript
- **Back-end:** Flask, YOLOv8, OpenCV
- **Data Labeling:** Roboflow

## Project Workflow

### STEP 1: Data Collection
Nine datasets are stored in "cdataset" folder to label them.

### STEP 2: Data Labeling
Datasets are labelled using roboflow and stored as train,valid,test in "CDATA" folder.

### STEP 3: Model Selection & Training
YOLOv8 is used as object detection model and is trained using labelled datasets in command prompt.

### STEP 4: Live Detection
Live detection code is created using YOLOv8 and Opencv.It contains the path of trained datasets.(live detction code in "myproject" folder).

### STEP 5: Front-End Development
User friendly interface is created to capture waste in real time and this front end is connected with flask backened for communication between server(batch file) and webpage(batch file is needed to run live detection on clicking "open camera" in webpage).
