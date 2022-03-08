# HRPlanes

This repo contains weights of YOLOv4 and Faster R-CNN networks trained with HRPlanes dataset. YOLOv4 training have been performed using Darknet (https://github.com/AlexeyAB/darknet). Faster R-CNN have been trained using TensorFlow Object Detection API v1.13 (https://github.com/tensorflow/models/tree/r1.13.0). 

# Dataset Details

The imagery required for the dataset has been obtained from Google Earth. We have downloaded 4800 x 2703 sized 3092 RGB images from the biggest airports of the world such as Paris-Charles de Gaulle, John F. Kennedy, Frankfurt, Istanbul, Madrid, Dallas, Las Vegas and Amsterdam Airports and aircraft boneyards like Davis-Monthan Air Force Base.
Dataset images were annotated manually by creating bounding boxes for each airplane using formerly HyperLabel software which still provides annotation services as Plainsight (https://app.plainsight.ai/). Quality control of each label was conducted by visual inspection of independent analysts who were not included in the labelling procedure. A total of 18,477 airplanes have been labelled. A sample image and corresponding minimum boxes for airplanes can be seen the figure.
The dataset has been approximately split as 70% (2166 images), 20% (615 images) and 10% (311 images) for training, validation and testing, respectively.


