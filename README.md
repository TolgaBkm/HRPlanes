# UPDATE

The HRPlanes Dataset can be downloaded now! Please see below for details!

# HRPlanes

This repo contains weights of YOLOv4 and Faster R-CNN networks trained with HRPlanes dataset. YOLOv4 training have been performed using Darknet (https://github.com/AlexeyAB/darknet). Faster R-CNN have been trained using TensorFlow Object Detection API v1.13 (https://github.com/tensorflow/models/tree/r1.13.0). 

# Dataset Details

The imagery required for the dataset has been obtained from Google Earth. We have downloaded 4800 x 2703 sized 3092 RGB images from the biggest airports of the world such as Paris-Charles de Gaulle, John F. Kennedy, Frankfurt, Istanbul, Madrid, Dallas, Las Vegas and Amsterdam Airports and aircraft boneyards like Davis-Monthan Air Force Base.
Dataset images were annotated manually by creating bounding boxes for each airplane using formerly HyperLabel software which still provides annotation services as Plainsight (https://app.plainsight.ai/). Quality control of each label was conducted by visual inspection of independent analysts who were not included in the labelling procedure. A total of 18,477 airplanes have been labelled. A sample image and corresponding minimum boxes for airplanes can be seen the figure.
The dataset has been approximately split as 70% (2166 images), 20% (615 images) and 10% (311 images) for training, validation and testing, respectively.

|  |  |
| --- | --- |
| ![alt text](https://github.com/TolgaBkm/HRPlanes/blob/main/Sample%20Images/Sample%20Image.png) | ![alt text](https://github.com/TolgaBkm/HRPlanes/blob/main/Sample%20Images/Sample%20Image%202.jpg) |
| ![alt text](https://github.com/TolgaBkm/HRPlanes/blob/main/Sample%20Images/Sample%20Image%203.jpg)|  ![alt text](https://github.com/TolgaBkm/HRPlanes/blob/main/Sample%20Images/Sample%20Image%204.jpg) |
| ![alt text](https://github.com/TolgaBkm/HRPlanes/blob/main/Sample%20Images/Sample%20Image%205.jpg) | ![alt text](https://github.com/TolgaBkm/HRPlanes/blob/main/Sample%20Images/Sample%20Image%206.jpg) |

# Download Weights

- YOLOv4 Weights and *.cfg* File: [Download](https://drive.google.com/file/d/1r0AlQE10y21b8bm5pvoj_jtDfDp_-ees/view?usp=sharing)
- Faster R-CNN Frozen Graphs: [Download](https://drive.google.com/file/d/1L3ho4L7lxxBItVg43zLmnrywQiYrxgWm/view?usp=sharing)

# Download The Dataset

You can now download the entire dataset in YOLO format from [Google Drive](https://drive.google.com/drive/folders/1NYji6HWh4HRLQMTagsn4tTv4LOdDrc9P?usp=sharing).

If you make use of the HRPlanes dataset, please cite our [paper](https://dergipark.org.tr/tr/pub/ijeg/issue/77206/1107890).

# Download Test Dataset

- YOLO Format: [Download](https://drive.google.com/file/d/1UBhs64ximEDmBtbMecg-aMaGMBX4yt8m/view?usp=sharing)
- TFRecord: [Download](https://drive.google.com/file/d/12MU8_cHpjai46hMsIdPY_X9T-Z6fEbRo/view?usp=sharing)

# Citation

If you make use of the test dataset or weights, please cite our [paper](https://dergipark.org.tr/tr/pub/ijeg/issue/77206/1107890#article_cite).

Bakırman, T. & Sertel, E. (2023). "A benchmark dataset for deep learning-based airplane detection: HRPlanes". International Journal of Engineering and Geosciences , 8 (3) , 212-223 . DOI: 10.26833/ijeg.1107890.

# Copyright

Use of the Google Earth images must respect the ["Google Earth" terms of use](https://about.google/brand-resource-center/products-and-services/geo-guidelines/). All images and their associated annotations can be used for academic purposes only, but any commercial use is prohibited.

Released under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0) License.](https://creativecommons.org/licenses/by-nc-nd/4.0/)
