# Coconut Tree Counting Using YOLOv9 and Flask

## Table of Contents
- [Introduction](#Introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

## Introduction
This project aims to count coconut trees in aerial images using the YOLOv9 object detection model. A Flask web application is provided to interact with the model, allowing users to upload images and receive counts and annotated images as output.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Python 3.9
- miniconda

## Installation
1. **Clone the Repository**
```bash
git clone https://github.com/adityale1711/YOLO-Coconut-Tree-Counting.git
cd YOLO-Coconut-Tree-Counting
```

2. **Create a Conda Environment**
```bash
conda create -n envname python=3.9
conda activate envname
```

3. **Install Required Packages**
```bash
pip install -r requirements.txt
```

4. **Download Coconut Tree model**
- Download Coconut Tree model and place them in the 'weights' directory.

## Usage
1. **Start the Flask Application**
```bash
python ./flashApp.py
```

2. **Upload Image or Video**
- Open your web browser and navigate to 'http://127.0.0.1:5000'
- Use the provide form to upload an image.

3. **Receive Results**
- After uploading, you will receive the count of detected coconut trees and an image/video annotated with circle point in the center of detected trees or bounding box around detected trees.
