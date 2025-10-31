# 🚗 Automatic Number Plate Detection (ANPD)
### 🏆 Built by Team Xception  
Developed at the **Hack the circle; A 24-Hour Khwopa Engineering College Hackathon**, Nepal

---

## 📖 Overview
**Automatic Number Plate Detection (ANPD)** is an AI-powered system designed to tackle the issue of **illegal parking at heritage sites** using machine learning and computer vision.  

Our solution automates the process of **detecting, extracting, and identifying vehicle license plates** from images or live video feeds — helping local authorities efficiently manage restricted parking zones and preserve Nepal’s heritage spaces.  

This project was developed during a **24-hour hackathon challenge** organized by **Khwopa Engineering College**, under the theme of using technology for **smart urban management**.

---

## ✨ Key Features
- 🔍 **Real-time Vehicle Detection** using advanced deep learning models  
- 🔠 **Automatic Number Plate Recognition (ANPR)** for text extraction from plates  
- 🧭 **Illegal Parking Detection** integrated with location-based monitoring  
- 🧰 **Lightweight & Efficient** — optimized for low-resource edge devices  
- 📸 Supports both **Static Images and Live Camera Feeds**

---

## 🧠 Tech Stack

| Category | Tools & Frameworks |
|-----------|--------------------|
| **Programming Language** | Python |
| **Machine Learning** | TensorFlow / Keras / Scikit-learn |
| **Computer Vision** | OpenCV, EasyOCR |
| **Model Architecture** | YOLO / CNN-based plate detector |

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```
git clone https://github.com/Trizan/Khwopa_Hackthon_ANPD.git
cd Khwopa_Hackthon_ANPD
```
## Install Dependencies
```
pip install -r requirements.txt
```

## Run the Application
```
python main.py
```

## 🔄 Workflow

Image Capture: Input an image or live stream feed from a camera

Vehicle Detection: Identify vehicles in the frame using a trained deep learning model

Plate Localization: Extract the region of interest (ROI) containing the license plate

Text Recognition: Perform OCR to extract alphanumeric characters from the plate

Illegal Parking Check: Compare detected vehicles with restricted zones or rules

Output: Display or store annotated frames and extracted plate numbers

## 🧑‍💻 Team Xception
| Name |	Role |
|--------------|--------------------|
| Trijan Koju | Computer Vision Developer |
| Bastav Khatiwada | Backend & Integration |
| Nirbhaya Sah |	UI/UX & Presentation |


## 🚀 Future Scope

Integrate GPS and geofencing for live parking violation alerts

Develop a centralized dashboard for authorities

Support for multilingual plate recognition (Nepali / Hindi)

Cloud deployment for large-scale monitoring

## 📜 License

This project is open source and available under the MIT License.

## 💬 Acknowledgements

Special thanks to Khwopa Engineering College for hosting the hackathon and encouraging innovation among students.
Inspired by the need to preserve Nepal’s cultural heritage through technology.

