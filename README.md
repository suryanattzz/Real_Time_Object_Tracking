# Real_Time_Object_Tracking

## Object Tracking Using YOLOv8 Model


## 📌 Project Description
This project implements real-time object tracking using **YOLOv8** and **OpenCV**. The model detects and tracks objects in a live video feed using a webcam.

## 🚀 Features
- Real-time object detection & tracking
- Uses **YOLOv8** for high accuracy
- Displays class names and confidence scores
- Assigns unique colors to different object classes
- Runs efficiently with OpenCV

## 🛠️ Setup and Installation
### **1️⃣ Install Dependencies**
Ensure you have Python installed (>=3.7), then install the required libraries:

```bash
pip install ultralytics opencv-python numpy
```

### **2️⃣ Clone the Repository**
```bash
git clone https://github.com/suryanattzz/Real_Time_Object_Tracking
cd Real_Time_Object_Tracking
```

### **3️⃣ Download YOLOv8 Model**
The pre-trained YOLOv8 model is already included in the repository. If you need to download it manually, use:
```bash
wget https://github.com/ultralytics/assets/releases/download/v8/yolov8s.pt
```

## 🎯 Usage

### **Run in Jupyter Notebook**
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open `yolo_object_tracking.ipynb` and run the cells step by step.


## 📌 Customization
- Modify `yolov8s.pt` to use a different model (e.g., `yolov8m.pt`, `yolov8l.pt`).
- Adjust confidence threshold (`box.conf[0] > 0.4`) for sensitivity tuning.
- Change colors in the `getColours()` function.

## 🛠️ Troubleshooting
- **Webcam not opening?** Ensure it's not being used by another program.
- **Performance issues?** Reduce image resolution or use a smaller YOLO model.
- **Module not found?** Run `pip install -r requirements.txt` to install dependencies.

