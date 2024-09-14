# Object-Detection-using-YOLO
Trained YOLO models to enhance Object Detection capabilities in Robots using both custom datasets and a dataset with a predefined boundaries

## Prequisites
1. YOLOv5 and YOLOv7 Libraries
2. Access to Jupyter Notebook or Google Colab

## Creating a Dataset
In order to perform Object detection on images using Roboflow we must first preprocess the Images. This can be done by either using Roboflow to create a custom boundaries or creating a JSON file with boundaries defined

### Custom Dataset using Roboflow
Roboflow can be used to preprocess images for training. In this project images over 100 images were preprocessed by segregating them into multiple categories based on color, robot type, size, etc. Images were labelled in Roboflow and custom boundaries were drawn based on what the robot needs to detect. The datasets were then segregated into Training, Validation, and Testing with a split of 70-15-15

### Creating a Dataset using JSOn
JSON files can be created which store various information about the robots such as the image number, the labeled group, as well their the 
co-ordinates of the boundary being detected
