# Flask YOLO and PixelLib Integration Project

## Overview

This project is a Flask-based web application that allows users to upload images and videos for **object detection** and **instance segmentation** using:
- **YOLO (You Only Look Once)** for object detection in videos.
- **PixelLib's Instance Segmentation** for images.

After the media files are uploaded, they are processed, and the application returns the processed media (segmented images or object-detected videos) back to the user.

## Features

- **Image Processing**: Performs instance segmentation on uploaded images (`.jpg`, `.jpeg`, `.png`) using PixelLib.
- **Video Processing**: Detects objects in videos (`.mp4`) using the YOLO model.
- **File Upload**: A user-friendly web interface for uploading images and videos.
- **Processed Output**: Returns processed media (image/video) to the user with detected objects or segmentations.

## Tech Stack

- **Flask**: Used as the web framework for the application.
- **OpenCV**: For image and video processing.
- **PixelLib**: Used for instance segmentation.
- **YOLO (You Only Look Once)**: Used for object detection in videos.
- **HTML**: To create the user interface for the app.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Chandhra2004/object-detection.git
   cd <object-detection>
