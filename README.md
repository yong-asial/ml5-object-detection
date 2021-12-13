# Object Detection with Javascript, the Easy Way!

If you are currently looking for an easy way to develop an object detection application using javascript, you are then coming to the right place. In this article, we will walk you step by step on how to build a simple yet elegant application that could detect 80 different classes of objects using just javascript.

[Read more](https://medium.com/the-web-tub/object-detection-with-javascript-the-easy-way-74fbe98741cf)

## ml5.js
ml5.js is the machine learning library in your web browser. It is built on top of tensorflow.js in which all the heavy-lifting or low-level tasks regarding machine learning are done in tensorflow.js. It is made for those who have no or little knowledge about machine learning.

## p5.js
P5.js is a library of Javascript. It is created to make it easy as possible for beginners to learn how to program interactive, graphical applications, to make a programming language more user-friendly by visualizing it. It provides functions that make JavaScript user life easy to draw in the web.

## Object detection
Object detection is a computer vision technique that works to identify and locate objects within an image or video. It identifies multiple objects as well as their locations by drawing bounding boxes around the detected ones. There are two pre-trained models within the ml5 objection detection method we can use. They are YOLO and COCO-SSD. Today we will use COCO-SSD.

### COCO-SSD
There are two terms in this method - COCO and SSD. First, COCO stands for Common Object in Context. It is large-scale object detection, segmentation, and captioning dataset. Next, SSD stands for Single-Shot Detector. It is the machine learning's object detection technique proposed by Wei Liu et al. So, COCO-SSD is a pre-trained model built from using the SSD technique trained with the COCO dataset. It could detect 80 different classes of objects. The classes are person, bicycle, car, cat, dog, bottle, etc.
