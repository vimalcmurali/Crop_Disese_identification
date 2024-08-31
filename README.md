# Crop_Disese_identification
# Plant Disease Detection Using Pre-trained CNN model (VGG16)

## Introduction
- Agricultural production rate plays a vital role in the economic
development of a country.
- The identification of plant diseases at an early stage is crucial for global health and wellbeing. So, controlling on the diseased leaves
during the growing stages of crops is a crucial step.
- Moreover, increasing crop production is essential to areas where food is scarce.
- Loss of crops from plant diseases would result in
reduction of income for crop producers, higher
prices for consumers and significant economic impact.
- The access to disease-control methods is limited
which results in annual losses of 30 to 50
percent for major crops in various countries. 
- Hence, detection of crop diseases is very crucial for economic development.


## Problem Statement
- Detect the crop diseases.
- Differentiate between various crop
diseases for a particular plant and then
for many various plants.
- Using object detection algorithms to find
the diseased area in the crop on the basis
of the features such as color, wilt, leaf
spots, unusual size of the leaf.
- Choosing appropriate neural network for
classification. 

## Objective
1. My Main Objective is that given the images of a specific crop, it
should classify it as a healthy crop or the disease it may be
infected with.
2. I have intend to use deep convolutional neural networks (D-CNN)
and some concepts of image processing to reach our goal of
identifying the disease of a plant using color, leaf spots, etc.
3. I have developed a web based application so that it can be used
widely by large number of people to determine crop diseases.



## Dataset Description

### Old Dataset
The dataset has different types of diseases for tomato leaves. There are 10 classes present which is shown below.

- Here goes the list:
  - Tomatomosaicvirus
  - Target_Spot
  - Bacterial_spot
  - TomatoYellowLeafCurlVirus
  - Late_blight
  - Leaf_Mold
  - Early_blight
  - Spidermites Two-spottedspider_mite
  - Tomato___healthy
  - Septorialeafspot

- The total number of images present are :
  - 10000 images for training data
  - 1000 images for validation data

- The data set contains the top 10 classes of diseases which are
highly occured on tomato plant.
- The images had taken with different angles, with different
backgrounds, and in different lighting conditions with an image size is 255 X 255 pixels.

For more details about the dataset, please refer the [**"Old Dataset"**][2].

[1]: https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf "Title"


### New Augmented Dataset

- Now, the datatset is augmented and the total images for training data are 18,345 images and for testing data are 4,585 images.

- Image Size 255 X 255

- A combination of picture flipping, rotation, blur, relighting, and
random cropping, image augmentation artificially builds training
images. In this, we scale, shear, zoom, and horizontally flip the
photos as part of the image augmentation process.

- The images were stored in the RGB image by

For more details about the dataset, please refer the [**"New Augmented Dataset"**][3].

[2]: https://www.kaggle.com/datasets/noulam/tomato "Title"



## Models Implemented

We have implemented 3 models successfully on tomato plant.
1. VGG-16
2. VGG-16-Fine-Tuning
3. VGG-19

For project demo, here is our web app - https://plant-disease-detection-webapp.streamlit.app/

[3]: https://github.com/bijaycd/Plant-Disease-Detection
