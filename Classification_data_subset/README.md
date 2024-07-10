# Nursing Behavior Classification Dataset

This repository contains a small dataset of images for training and validating a classification model to detect nursing behavior of sow within farrowing crate. The dataset is organized into two main folders: Train and Val. Each of these folders contains 12 subfolders, corresponding to different classes.

**Folder Structure**

- Train/
  - Lying_Left_Not_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Lying_Left_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Lying_Right_Not_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Lying_Right_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Sitting_Not_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Sitting_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Standing_Not_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Standing_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Sternal_Lying_Partially_Left_Not_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Sternal_Lying_Partially_Left_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Sternal_Lying_Partially_Right_Not_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Sternal_Lying_Partially_Right_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg

- Val/
  - Lying_Left_Not_Nursing/
    - image1.jpg
    - image2.jpg
  - Lying_Left_Nursing/
    - image1.jpg
    - image2.jpg
  - Lying_Right_Not_Nursing/
    - image1.jpg
    - image2.jpg
  - Lying_Right_Nursing/
    - image1.jpg
    - image2.jpg
  - Sitting_Not_Nursing/
    - image1.jpg
    - image2.jpg
  - Sitting_Nursing/
    - image1.jpg
    - image2.jpg
  - Standing_Not_Nursing/
    - image1.jpg
    - image2.jpg
  - Standing_Nursing/
    - image1.jpg
    - image2.jpg
  - Sternal_Lying_Partially_Left_Not_Nursing/
    - image1.jpg
    - image2.jpg
  - Sternal_Lying_Partially_Left_Nursing/
    - image1.jpg
    - image2.jpg
  - Sternal_Lying_Partially_Right_Not_Nursing/
    - image1.jpg
    - image2.jpg
  - Sternal_Lying_Partially_Right_Nursing/
    - image1.jpg
    - image2.jpg

- Test_Images/
    - image1.jpg
    - image2.jpg
    - image3.jpg
    - image4.jpg

**Note:** To train the classification model, only the `Train` and `Val` folders are needed. The `Test_Images` folder contains 4 new images to check the model performance or to see how well the model detects the unseen images.

You can use the [Sow_Nursing_Behavior_Classification.ipynb](Sow_Nursing_Behavior_Classification.ipynb) Google Colab notebook to help in training the classification model using this dataset.

For an alternative approach to training a classification model without writing code, you can use [this website](https://tm.gen-ai.fi/image/general) where you can simply upload the images and train the model. You can also test the model using the images from the `Test_Images` folder.


