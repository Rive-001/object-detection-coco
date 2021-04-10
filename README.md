# Object detection using an open-source deep neural network

This tutorial will introduce the concept of Object Detection and will demonstrate the application of pre-trained models. Object detection is the task of identifying objects of interest in an image, outside of the background. It is a regression task, where we are trying to predict a set of two points on the image for each object. These two points define the bounding box that encapsulates the object. Object Detection is an important task in fields such as autonomous driving and pathology. In the former, we want to know the position of cars, pedestrians and traffic lights with respect to the vehicle. In the latter, we might want to isolate tumor elements in oncological pathology images.

<div align="center"><img src="https://github.com/Rive-001/object-detection-coco/blob/main/coco-dataset-example.png" width="800" height="400"></div>
<div align="center"><b>COCO dataset examples</b></div>

## Technology Stack
* **Language and Frameworks**: Python, Pytorch
* **Visualization**: [OpenCV](https://opencv.org/), [sci-kit image](https://scikit-image.org/)
* **Datasets**: [COCO Detection 2017](https://cocodataset.org/#home), [Penn-Fudan Database](https://www.cis.upenn.edu/~jshi/ped_html/)

## Contents

This tutorial will cover the following topics:

1. **Installing libraries**: Where we download the dataset and install the necessary pre-requisites.
2. **COCO Dataset**: Where we go over the COCO dataset and format while exploring the usage of the COCO API.
3. **Faster R-CNN model**: We will use Pytorch's pre-trained [Faster R-CNN](https://pytorch.org/vision/stable/models.html#object-detection-instance-segmentation-and-person-keypoint-detection) model to perform object detection.
4. **Example Application: Pedestrian Detection**: We will use the Faster R-CNN model to only detect pedestrians in another dataset.
5. **Summary and References**

## Summary

This tutorial introduces the Object Detection task and the COCO dataset and format. It also demonstrates how we could use pre-trained machine learning models to perform inference on our own datasets.
