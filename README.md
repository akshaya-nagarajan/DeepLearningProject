
# Project : Yoga Pose Classification

## Team Members:
Akshaya Nagarajan, Asha Aher, Swati Narkhede

## Presentation Link:
https://drive.google.com/open?id=1jRx606jaa0_DVXIb2mGKzbasU2F63fGh

## PPT:
https://github.com/akshaya-nagarajan/DeepLearningProject/blob/master/DL_final_deck.pptx

## Data:
- https://drive.google.com/drive/folders/1efJppHFuznQqAYXkSTepx68mCkSKAO_M?usp=sharing

## Files:
1. Data Collection, Cleaning, Preprocessing 
- https://github.com/akshaya-nagarajan/DeepLearningProjects/blob/master/Project/DLProjectDatasetPreprocessing.ipynb

2. Train - Test Split Folders 
- https://github.com/akshaya-nagarajan/DeepLearningProjects/blob/master/Project/DLProjectTrainTestSplit.ipynb

3. Models - 

    #### InceptionV3:
    - 2 Classes: https://github.com/akshaya-nagarajan/DeepLearningProject/blob/master/DLProjectTransferLearningModelInceptionModel.ipynb
    - Multi-Class(9 classes): https://github.com/akshaya-nagarajan/DeepLearningProject/blob/master/DLProjectTransferLearningModelInceptionMultiClass.ipynb
    - Multi-Class(4 classes): https://github.com/akshaya-nagarajan/DeepLearningProject/blob/master/DLProjectTransferLearningModelInceptionModelFourClass.ipynb
    - Multi-Class(3 classes): https://github.com/akshaya-nagarajan/DeepLearningProject/blob/master/DLProjectTransferLearningModelInceptionModelWithThreeClass.ipynb

    #### VGG16: 
    - 2 Classes: https://github.com/akshaya-nagarajan/DeepLearningProject/blob/master/DLProjectTransferLearningModelVGGModel.ipynb
    - Multi-Class(9 classes): https://github.com/akshaya-nagarajan/DeepLearningProject/blob/master/DLProjectTransferLearningModelVGGModelMultiClass.ipynb
    
    #### CNN:
    - Multiclass(9 classes): https://github.com/akshaya-nagarajan/DeepLearningProject/blob/master/Yoga_pose_classification_with_CNN.ipynb

## Web App Code:
- https://github.com/akshaya-nagarajan/DeepLearningProject/tree/master/Deployment-Deep-Learning-Model

## Prerequisites for web deployment:
1.  Install below dependecies:
    1. matplotlib
    2. Keras
    3. Tensorflow
    4. Pillow
2. To load the model in flask application, please upload the saved model file (model.h5) in the directory before exectution of flask code.

## Tensorboard Uploads:
1. https://tensorboard.dev/experiment/MGheONk3Qm2yXvG0WALsVw/#scalars
2. https://tensorboard.dev/experiment/ll6KJrPMS2Wqc3c9JGClsA/
3. https://tensorboard.dev/experiment/zOS2EHgeRUqalb1qW2ZqVw/#scalars

## Visualizations:

### Class Distribution
![Class Distribution](https://user-images.githubusercontent.com/57167636/82406057-863a0d00-9a1a-11ea-9422-740c393219a0.png)

### Class Distribution
![Class Distribution](https://user-images.githubusercontent.com/57167636/82406060-8803d080-9a1a-11ea-8e92-4c87728e7592.png)

### Confusion Matrix
![Confusion Matrix](https://user-images.githubusercontent.com/57167636/82406062-889c6700-9a1a-11ea-9b49-02bbaff9452d.png)

### Confusion Matrix
![Confusion Matrix](https://user-images.githubusercontent.com/57167636/82406064-889c6700-9a1a-11ea-90bf-f7acd2301085.png)

## Results

Approaches  | 1 | 2  | 3 | 4 | 5
------------- | ------------- | ------------- | -------------  | ------------- | -------------
Model | CNN | VGG16 model with 2 classes | InceptionV3 model with 2 classes  | InceptionV3 model with all classes | VGG16 model with all classes
Result | 86% | 57% | 86% | 19% | 32%


### Web App Screens
![Web App](https://user-images.githubusercontent.com/57167636/82527949-860a4200-9aec-11ea-9faa-efbcbb2beec5.png)
![Web App](https://user-images.githubusercontent.com/57167636/82527943-81de2480-9aec-11ea-81bc-43cc364d5f45.png)
![Web App](https://user-images.githubusercontent.com/57167636/82527947-84d91500-9aec-11ea-959d-2d8440b7a25b.png)


