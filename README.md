# 🚀 SmartVisionSearch-YOLO11
SmartVisionSearch-YOLO11 is a powerful computer vision search engine built on YOLO11 for real-time object detection, combined with an interactive Streamlit interface. Upload an image, detect objects instantly from the COCO dataset (80 classes), and explore results with clear bounding boxes and predictions.

# ✨ Features
•	🔍 YOLO11-powered detection for fast and accurate object recognition

•	📚 Supports 80 COCO object categories

•	🖼️ Streamlit-based UI for seamless image upload and search

•	🛠️ Modular codebase for easy customization and extension

•	⚡ Works on both CPU and GPU environments

# 📂 Project Structure
•	app.py → Streamlit application (UI layer)

•	inference.py → Model loading & detection logic

•	utils.py → Preprocessing, visualization, and helper functions

•	config.py → Configurations for paths, thresholds, and parameters

# ⚙️ Installation
### 1. Create Environment (GPU Recommended)
```
conda create -n smartvision_env python=3.11 -y
conda activate smartvision_env
conda install pytorch==2.5.1 torchvision==0.20.1 pytorch-cuda=12.4 -c pytorch -c nvidia
pip install -r requirements.txt
```

### 2. Run the Application
```
streamlit run app.py
```

# 📦 Dependencies
•	torch

•	torchvision

•	streamlit

•	Other required packages listed in requirements.txt

# 🚀 Usage
•	Upload an image via the Streamlit interface

•	Select objects to search (from COCO categories)

•	View detected objects with bounding boxes & predictions in real time

# 🌟 Demo Preview
Imagine uploading an image → selecting "dog" → instantly seeing bounding boxes highlighting detected dogs. 

That’s the speed and accuracy of SmartVisionSearch-YOLO11.
