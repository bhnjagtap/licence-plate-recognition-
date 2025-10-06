# License Plate Recognition with YOLO + OCR

📘 **Overview**  
This system detects vehicles’ license plates in real-time using the YOLO object detection model. Once a plate is detected, it extracts the plate region and uses OCR (Optical Character Recognition) to read and display the license number.  

The result is shown in a live annotated video feed with bounding boxes and the recognized plate number displayed above each vehicle.

---

🎯 **Features**  

- ✅ Real-time license plate detection using YOLO  
- ✅ Automatic text extraction with EasyOCR  
- ✅ Works with webcam or video files  
- ✅ Displays bounding boxes and recognized numbers on screen  
- ✅ Optimized for better speed and accuracy  

---

🧠 **Tech Stack**  

- **Python 3.x**  
- **OpenCV** — For video processing and visualization  
- **YOLOv8 / YOLOv5** — For license plate detection  
- **EasyOCR** — For optical character recognition  
- **NumPy** — For image array operations  
- **PyTorch** — Backend framework for YOLO  

---

⚙️ **Installation**

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/License-Plate-Recognition-YOLO-OCR.git
cd License-Plate-Recognition-YOLO-OCR
