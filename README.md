# Computer-Vision
Ds-473: Computer Vision Project


OBJECTIVE
The objective of this project is to evaluate the performance of CNN, YOLO, and R-CNN models on object detection and classification tasks using the PASCAL VOC dataset. By analyzing accuracy, speed, and resource demands, we aim to identify the most effective model for multiple object detection challenges, offering insights into model selection for computer vision applications with various real-world constraints.


INTRODUCTION
In this project, we explore the application of various machine learning models in the field of computer vision, focusing on object detection and classification tasks. We employ Convolutional Neural Networks (CNNs) for image classification, YOLO (You Only Look Once) for single object detection, and R-CNN (Region-based Convolutional Neural Network) for multiple object detection. Our dataset includes labeled images with diverse object classes, providing an ideal foundation to evaluate the strengths and limitations of each model. Through this project, we aim to compare model accuracy, speed, and suitability for different tasks, offering insights into the effectiveness of deep learning models in practical computer vision applications.


DATA
For our project we have selected PASCAL VOC (Visual Object Classes) dataset for training and evaluating the models. This dataset is a widely used benchmark in computer vision, designed for object detection, classification, and segmentation tasks. It contains annotated images spanning 20 different object categories, including animals, vehicles, and household items, with detailed bounding boxes and labels for each object instance. This dataset offers a rich variety of complex real-world scenes, making it ideal for training and evaluating machine learning models in object recognition and detection challenges. We preferred PASCAL VOC over COCO dataset because it is light weight as compared to COCO which contains over 80 classes and are much more complex for our current resources. Initially all images shape is not harmonized (i.e. different shape for different image in data).
