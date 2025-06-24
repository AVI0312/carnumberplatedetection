# Car Numberplate Detection

A comprehensive system for detecting and recognizing number plates in video streams using YOLO for object detection and Tesseract for OCR.

## 🧠 Project Overview

This project provides an end-to-end solution for automatic number plate recognition (ANPR). It captures frames from a video, detects number plates using YOLO, extracts text using OCR, and logs the results. The system ensures data consistency by cleaning up images without corresponding text files.

### 🚀 Key Features

- **Frame Extraction:** Captures and saves frames from a video file.
- **Object Detection:** Uses YOLO to detect number plates in video frames.
- **OCR Integration:** Employs Tesseract for text recognition in detected regions.
- **Data Logging:** Records detected number plates with timestamps.
- **Data Cleanup:** Ensures only valid image-text pairs are retained.

## 🛠️ Tech Stack

- **OpenCV (cv2):** For video processing and image manipulation.
- **Pandas:** For handling detection data.
- **Ultralytics YOLO:** For object detection.
- **Tesseract-OCR:** For text recognition.
- **NumPy:** For numerical operations.
- **DateTime:** For logging timestamps.
- **OS Module:** For file operations and directory management.

## 📦 Installation

### Prerequisites

- Python 3.8+
- OpenCV
- YOLOv8 (best.pt model)
- Tesseract OCR

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/number-plate-recognition.git
   cd number-plate-recognition
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download YOLO model:
   ```bash
   wget https://github.com/ultralytics/yolov8/releases/download/v0.0.1/best.pt
   ```

4. Install Tesseract OCR:
   - **Ubuntu/Debian:**
     ```bash
     sudo apt-get install tesseract-ocr
     ```
   - **Windows:**
     Download from [here](https://github.com/UB-Mannheim/tesseract/wiki) and add to PATH.


## Dataset link:  
https://drive.google.com/file/d/1m4n4IN2WaS7RviR_8TH6Jze_mP4GvMLG/view?usp=sharing , https://drive.google.com/file/d/17zBwSwJCr4KY_KdGppLmPy9T8_Tr5MVx/view?usp=sharing
![Screenshot (421)](https://github.com/user-attachments/assets/6ea7543d-4690-47c4-b19e-b638316b755e)
![Screenshot (422)](https://github.com/user-attachments/assets/8e6e92b4-bbe0-4d1b-a41a-820a6e85c9de)
![Screenshot (423)](https://github.com/user-attachments/assets/bcdf697d-863b-4cd2-8fb9-a9107caad90d)
![Screenshot 2024-10-16 003545](https://github.com/user-attachments/assets/e7134fb3-676c-4eb1-a53d-049a3dcb6dda)
