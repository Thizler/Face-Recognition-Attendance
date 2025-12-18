# 🎓 Face Recognition Attendance System
> ระบบเช็คชื่อด้วยการจดจำใบหน้า (AI-powered Attendance System)

ระบบเช็คชื่ออัตโนมัติด้วย **Face Recognition**  
พัฒนาโดยใช้ **Python, OpenCV และ Deep Learning (Siamese Network)**  
เหมาะสำหรับใช้งานในห้องเรียน หรือเป็นโปรเจคด้าน **AI / Computer Vision**

---

## ✨ Features
✅ ตรวจจับใบหน้าด้วย Haar Cascade  
✅ จดจำใบหน้าด้วย Siamese Neural Network  
✅ บันทึกเวลาเข้าเรียนอัตโนมัติ  
✅ แสดงผลผ่าน Web Application  
✅ ใช้โมเดลที่ฝึกไว้แล้ว (Pre-trained Model)

---

## 🧠 Technologies
| Category | Tools |
|-------|------|
| Language | Python |
| AI / ML | PyTorch, Siamese Network |
| Computer Vision | OpenCV |
| Web Framework | Flask |
| Data | NumPy, Pandas |

---

## 📁 Project Structure
Face-Recognition-Attendance/  
│  
├── app.py # Main Flask Application  
├── model.py # AI Model (Siamese Network)  
├── utils.py # Helper functions  
├── haarcascade_frontalface_default.xml  
│  
├── siamese_model.pth # Trained Siamese Model  
├── face_encoder.pt # Face Encoder  
├── face_db.pt # Face Database  
│  
├── attendance.csv # Attendance Record  
│  
├── templates/ # HTML Templates  
├── static/ # CSS / JS / Assets  
└── README.md  
  
---

## ⚙️ Installation

### 🔹 1. Clone Repository
```bash
git clone https://github.com/Thizler/Face-Recognition-Attendance.git
cd Face-Recognition-Attendance
```
### 🔹 2. Install Dependencies
```bash
pip install flask opencv-python torch torchvision numpy pandas
```
▶️ Run the Project
```bash
python app.py
```
เปิดเว็บเบราว์เซอร์:

```cpp
http://127.0.0.1:5000
```

📝 Attendance Output
ข้อมูลการเช็คชื่อจะถูกบันทึกลงไฟล์ attendance.csv

ตัวอย่างข้อมูล:

Name	Date	Time
Student01	2025-01-01	08:30:15

🎯 Use Cases
📚 ระบบเช็คชื่อในห้องเรียน

🧑‍🎓 ระบบยืนยันตัวตน

🤖 โปรเจคด้าน AI / Computer Vision

🎓 Mini / Final Project
