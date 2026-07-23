# VisionAi – AI-Powered Object Detection Web App

## Project Overview

VisionAi is a browser-based object detection web application that uses Artificial Intelligence to identify and classify objects in real time. The application runs entirely in the browser using TensorFlow.js, allowing users to perform object detection through a webcam or uploaded images without installing additional software.

## Problem Statement

Real-time object detection applications often require high-end hardware, dedicated software, or cloud-based processing, making them less accessible for students and developers. Many existing solutions are expensive, platform-dependent, or require complex installation procedures.

## Solution

VisionAi provides a lightweight and user-friendly solution by performing object detection directly in the browser. Using TensorFlow.js with the COCO-SSD and MobileNet models, the application can detect multiple objects in real time while maintaining good performance on modern web browsers.

## Features

- Real-time object detection using webcam
- Image upload for object detection
- Bounding box visualization
- Detection history
- Separate settings page
- Lightweight browser-based application
- Responsive dark-themed user interface

## Tech Stack

### Frontend

- HTML
- CSS
- JavaScript

### AI & Machine Learning

- TensorFlow.js
- COCO-SSD
- MobileNet

### Development Tools

- Git
- GitHub
- Visual Studio Code

## Working Principle

The application loads the pre-trained COCO-SSD model through TensorFlow.js when the webpage is opened. Users can either enable their webcam or upload an image for analysis. The model processes each frame or image, identifies objects, predicts their classes, and displays the results with bounding boxes and confidence scores. The detected objects are also stored in the history section for later reference.

## Applications

- Smart surveillance systems
- Educational AI projects
- Object recognition demonstrations
- Web-based AI applications
- Computer vision learning

## Learning Outcomes

- Browser-based AI implementation
- TensorFlow.js model integration
- Real-time image processing
- JavaScript DOM manipulation
- Computer vision fundamentals
- Frontend web development

## Limitations

- Detection accuracy depends on lighting conditions.
- Performance varies based on device specifications.
- Limited to the object classes available in the COCO dataset.
- Browser performance may affect real-time detection speed.

## Future Enhancements

- Custom object detection models
- Face recognition support
- Video file detection
- Object counting
- Voice feedback
- Performance optimization
- Mobile application support

## Conclusion

VisionAi demonstrates how Artificial Intelligence can be integrated into web applications using TensorFlow.js to provide real-time object detection without requiring additional software or specialized hardware. The project offers an accessible and lightweight solution for learning and experimenting with computer vision directly in a web browser.
