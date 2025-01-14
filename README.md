# Object_Tracking

### 🚀 Object Tracking Project using OpenCV and Euclidean Distance Tracker

This project focuses on object detection and tracking using OpenCV's background subtraction technique and a custom Euclidean Distance Tracker. It tracks objects in a stable video feed by identifying moving objects and associating them across frames.

#### 📋 Project Overview

###### The goal of this project is to:

###### Detect moving objects from a stable camera (background remains static).
###### Track detected objects using the Euclidean distance method to associate objects across frames.
###### Implement a simple but effective tracking algorithm that can handle basic object tracking scenarios.
#### 📌 How it Works:
### Object Detection:
###### The project uses OpenCV’s BackgroundSubtractorMOG2 to detect objects by subtracting the background from each frame of the video.
###### Object Tracking:
###### The custom EuclideanDistTracker keeps track of objects across frames by calculating the distance between their positions.
