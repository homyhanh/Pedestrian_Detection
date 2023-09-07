# Pedestrian_Detection

## Introduction
Pedestrian detection is the task of object detection. In recent years, with the rapid development of deep learning, Pedestrian Detection Technology has also great progress. It is an important foundation in many fields, such as self-driving cars, intelligent monitoring systems, and robot development. For self-driving car systems, walker detection is very important so that vehicles can dodge them to minimize accidents.

## Dataset
Use dataset [Caltech Pedestrian Detection Benchmark](https://drive.google.com/drive/folders/1DJdXeICoSBzVk65F1HE6YMn6FkxBHvpb?usp=sharing)
Dataset includes images cropped from a video with frame size of 640x480 px. There are d approximately 10 hours of 30Hz video (∼106 frames) taken from a vehicle driving through regular traffic in an urban environment.

## Method
Use features extraction (Histogram of Oriented Gradient, Local Binary Patterns) on a SVM classifier
