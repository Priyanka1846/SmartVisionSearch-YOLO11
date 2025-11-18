# SmartVisionSearch-YOLO11

SmartVisionSearch-YOLO11 is a computer vision search engine that uses YOLO11 for real-time object detection and Streamlit for an interactive web interface.
Upload an image and instantly identify objects from the COCO dataset, with clear bounding boxes and predictions.

## Features

•	YOLO11-powered detection for accurate object recognition

•	Supports 80 COCO object classes

•	Streamlit-based UI for easy image upload and search

•	Modular code for easy customization and extension

•	Works on both CPU and GPU environments

## Project Structure

•	app.py → Streamlit application for user interface

•	inference.py → Loads the model and handles detection logic

•	utils.py → Utility functions for preprocessing, visualization, etc.

•	config.py → Configurations for paths, thresholds, and parameters

## Installation Instructions
1. Create Environment (GPU)
```
conda create -n smartvision_env python=3.11 -y
conda activate smartvision_env
conda install pytorch==2.5.1 torchvision==0.20.1 pytorch-cuda=12.4 -c pytorch -c nvidia
pip install -r requirements.txt
```

3. Run the App
streamlit run app.py

## Dependencies

•	torch

•	torchvision

•	streamlit

•	Other required packages listed in requirements.txt

## Usage

•	Upload an image in the Streamlit interface

•	Select objects to search (from COCO categories)

•	View detected objects with bounding boxes in real time
