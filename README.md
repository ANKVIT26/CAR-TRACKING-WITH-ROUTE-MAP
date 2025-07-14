# CAR-TRACKING-WITH-ROUTE-MAP

A comprehensive vehicle tracking system that utilizes advanced computer vision and OCR technology to detect and log vehicle number plates from video feeds. The system provides real-time number plate recognition, database logging, route mapping, and performance analysis through confusion matrices.


# Features

Real-time Number Plate Detection - Advanced OCR-based detection using EasyOCR for accurate text recognition from video frames
Database Logging - Automatic storage of detected plates with timestamps in SQLite database
Image Archival - Saves detected plate images for future reference and analysis
Performance Analytics - Generates confusion matrices to evaluate detection accuracy
Route Visualization - Interactive mapping functionality to display vehicle routes from point A to G
Frame Processing Optimization - Processes every 5th frame for efficient performance without compromising accuracy.

# Core Libraries

OpenCV (opencv-python) - Computer vision and image processing
EasyOCR (easyocr) - Optical Character Recognition for text detection
Tesseract (pytesseract) - OCR engine support
PyTorch (torch, torchvision) - Deep learning framework for EasyOCR

# Data & Analytics

SQLite3 - Database for vehicle logs and timestamp storage
NumPy - Numerical computing and array operations
Matplotlib - Data visualization and confusion matrix plotting
Scikit-learn - Machine learning metrics and performance evaluation

# Mapping & Visualization

Folium - Interactive map generation and route visualization
Google Colab patches - Image display compatibility


# Installation
bash# Install required packages
pip install opencv-python pytesseract matplotlib scikit-learn folium easyocr torch torchvision

# Install Tesseract OCR (Ubuntu/Debian)
apt-get install tesseract-ocr libtesseract-dev

# Output Files

detected_plates/ - Directory containing captured plate images    
route_map.html - Interactive route visualization      
vehicle_tracking.db - SQLite database with detection logs

# System Requirements

Google Collab or Jupyter Notebook
Python 3.7+
Sufficient storage for video processing and image archival
GPU support recommended for faster PyTorch operations

# Output images
<img width="677" height="590" alt="image" src="https://github.com/user-attachments/assets/994fa8c6-e76c-425e-b1b9-b867447b20d1" />
<img width="1184" height="762" alt="image" src="https://github.com/user-attachments/assets/026bb7da-5550-4d89-b745-5545f3319ab1" />


