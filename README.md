# 🛣️ AI-Powered Toll Collection System

An intelligent toll collection system designed to automate vehicle classification at toll booths using computer vision and AI. This lightweight and efficient model identifies vehicle types (e.g., car, van, truck, taxi, bus) through image analysis — eliminating the need for manual classification by toll booth staff.

## 🚀 Features

- 🤖 **AI-based Vehicle Classification**: Uses machine learning to accurately detect and categorize vehicles from live camera feeds.
- 📷 **Camera Integration**: Captures real-time images for processing without relying on License Plate Recognition (LPR).
- 💻 **Laptop-Friendly**: Designed to run efficiently on standard laptops, making it ideal for deployment in small-scale or mobile toll setups.
- 🔍 **Modular Design**: Easy to integrate with existing toll collection systems or expand with additional modules like payment or logging.
- 🧠 **Simplified Model**: Focused on vehicle type detection only — keeping the system streamlined and fast.

## 🧩 Modules

- **Image Capture Module** – Captures frames from connected cameras.
- **Vehicle Detection Module** – Processes images to classify vehicle types.
- **User Interface** – Displays classification results or integrates with barrier control systems.

## 🔧 Technologies Used

- Python
- OpenCV
- TensorFlow / PyTorch (based on chosen model)
- Webcam or IP camera for image input

## ✅ Software Requirements

- **XAMPP** (Install **Apache** and **MySQL** server)
- **Python 3.10** or above (ensure `pip` is installed)

---

## 📦 Python Libraries Used

The following libraries are used in this project:

```python
import sys 
import os
import numpy as np
import tkinter as tk
from tkinter import ttk
from PIL import Image, ImageTk
from tensorflow.keras.models import load_model
import cv2 as cv
from ultralytics import YOLO


import pymysql
import pygame
import time
from decimal import Decimal
import datetime
```

## 🔧 Installation Guide

Follow these steps in your Command Prompt to install all required libraries:

```bash
pip install numpy
pip install pillow
pip install tensorflow
pip install opencv-python
pip install ultralytics
pip install pymysql
pip install pygame
```

## 🛠️ System Setup Instructions

Follow these steps to set up and explore the AI-Powered Toll Collection System:

### 📁 Step-by-Step Setup

1. **Extract** the `try.zip` folder into the following directory: C:\xampp\htdocs
   
2. **Open XAMPP Control Panel** and click **Start** on both **Apache** and **MySQL** to run the local server and database services.

3. In XAMPP, click **Admin** next to **MySQL** to open **phpMyAdmin** in your browser.

4. In phpMyAdmin:
- Click **New** to create a new database.
- Name it:
  ```
  tollcollectionsystem
  ```
- Click **Import**, and choose the `tollcollectionsystem.sql` file to import the database structure and data.

5. Open a browser tab and enter the following local URL to access the system's web interface: C:/xampp/htdocs/try/model.html

6. ✅ **You're all set!** You can now explore and interact with the AI-powered toll collection system.

> 💡 Make sure your browser allows local file access and that Apache/MySQL are running.

---

“🎥 System Demo -------------- You can watch a video demonstration of the system here: 🔗 [Watch on YouTube](https://www.youtube.com/watch?v=MjdhIVKxQho&t=1s)”
