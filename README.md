<H1 align="center">Fire Detection using YOLOv8</H1>

YOLOv8 re-implementation

### Installation
! pip install ultralytics

! pip install pycocotools

### Results

| Version | Epochs | Box mAP |                                                                                  Download |
|:-------:|:------:|--------:|------------------------------------------------------------------------------------------:|
|  v8_n   |  500   |    37.0 |                                                                [model](./weights/best.pt) |
|  v8_n*  |  500   |    37.2 | [model](https://github.com/jahongir7174/YOLOv8-pt/releases/download/v0.0.1-alpha/v8_n.pt) |
|  v8_s*  |  500   |    44.6 | [model](https://github.com/jahongir7174/YOLOv8-pt/releases/download/v0.0.1-alpha/v8_s.pt) |
|  v8_m*  |  500   |    50.0 | [model](https://github.com/jahongir7174/YOLOv8-pt/releases/download/v0.0.1-alpha/v8_m.pt) |
|  v8_l*  |  500   |    52.5 | [model](https://github.com/jahongir7174/YOLOv8-pt/releases/download/v0.0.1-alpha/v8_l.pt) |
|  v8_x*  |  500   |    53.5 | [model](https://github.com/jahongir7174/YOLOv8-pt/releases/download/v0.0.1-alpha/v8_x.pt) |


<H1 align="center"> Dataset </H1>
About dataset: https://www.kaggle.com/datasets/lamdo2k3/dataset-fire-detection-usingyolo
The Fire Detection Dataset is an essential resource designed for training and testing fire detection models. This dataset is divided into three main sections: images, labels, and data_fire.yaml (configuration file).

1. Images:

Train: This directory contains 300 images used for training the model. They are labeled as "train".
Validation: This directory contains 10 images used to validate the model's performance. They are labeled as "val".
Test: This directory contains 52 images used to test the trained model. They are labeled as "test".

2. Labels:

The labels correspond to the images contained in the images directory.
The "train" directory contains labels for training images.
The "val" directory contains labels for validation images.
Each label file is a text file (.txt) containing information about the location and characteristics of fires in the corresponding images.

3. data_fire.yaml (Configuration File):

This is the configuration file for the Fire Detection Dataset.
It contains information about the dataset's structure, necessary parameters, and other related settings.
This dataset provides a crucial resource for developing and evaluating fire detection models. Utilizing the images and their corresponding labels during training and testing will help improve the performance of fire detection models.

### Dataset structure

    ├── data 
        ├── Fire_data
            ├── images
                ├── test
                    ├── 1111.jpg
                    ├── 2222.jpg
                ├── train
                    ├── 1111.jpg
                    ├── 2222.jpg
                ├── val
                    ├── 1111.jpg
                    ├── 2222.jpg
            ├── labels
                ├── test
                    ├── 1111.txt
                    ├── 2222.txt
                ├── train
                    ├── 1111.txt
                    ├── 2222.txt
                ├── val
                    ├── 1111.txt
                    ├── 2222.txt
                ├── train.cache
                ├── val.cache
            ├── data_fire.yaml

        
        
            
        
        





                
