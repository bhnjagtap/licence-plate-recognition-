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

▶️ **How to Run**

- **Place your YOLO weights file (e.g., best.pt) in the project directory.**

- **Open the terminal inside the folder.**

 **Run the script:**

```bash
 python easyocryoloLIVE.py

```
The webcam window will open — showing live detection and the recognized plate numbers.

📂 **Project Structure**

```bash
License-Plate-Recognition-YOLO-OCR/
│
├── easyocryoloLIVE.py        # Main script
├── best.pt                   # YOLO trained weights
├── requirements.txt
├── README.md
└── sample_video.mp4          # (optional) demo video
```

🧩 How It Works

YOLO Detection → Detects the bounding box of the license plate

ROI Extraction → Crops the detected plate region

Preprocessing → Converts the region to grayscale and denoises it

OCR Recognition → Uses EasyOCR to extract text from the cropped image

Display → Draws bounding boxes and overlays the recognized number in the live video feed
