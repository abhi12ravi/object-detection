
# Object detection assignment

## Task description:
```
Object Detection is one of the fundamental tasks in computer vision with applications
ranging across medicine, robotics, and many others. In this task, you are given a dataset that
consists of images containing people and cars. The goal of this task is to train a model that
can localize and classify each instance of person and car as accurately as possible.
```


## Goals of this assignment
1. To develop a ML model that can detect persons and cars as accurately as possible.


## Approach
The approach was to use state-of-the-art object detection models like resnet and yolo, use transfer learning to predict only the required labels. 

Dataset is available [here](https://evp-ml-data.s3.us-east-2.amazonaws.com/ml-interview/openimages-personcar/trainval.tar.gz).

## Solution
1. Approach 1 - [resnet pre-trained model](https://github.com/abhi12ravi/object-detection/blob/main/notebooks/object_detection_using_resnet.ipynb)
2. Approach 2 - [yolo v3 pre-trained model ](https://github.com/abhi12ravi/object-detection/blob/main/notebooks/detections_yolov3.ipynb)
3. Approach 3 - [yolo v3 custom trained model ](https://github.com/abhi12ravi/object-detection/blob/main/notebooks/yolo_object_detection_.ipynb)

## Comment
The approach 3 could not be successfully implemented because the training process could not be completed on Google Colab.


## References
1. [COCO documentation](https://arxiv.org/pdf/1405.0312.pdf)
2. [COCO to VOC annotations convertor](https://pypi.org/project/imgann/)
3. [bbox-visualizer](https://bbox-visualizer.readthedocs.io/en/latest/)
