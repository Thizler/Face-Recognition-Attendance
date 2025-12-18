🎓 Face Recognition Attendance System

ระบบเช็คชื่อด้วยการจดจำใบหน้า (Face Recognition Attendance System)
พัฒนาโดยใช้ Python และ AI / Deep Learning เพื่อระบุตัวตนจากกล้องและบันทึกการเข้าเรียนอัตโนมัติ

📌 Features

ตรวจจับใบหน้าด้วย Haar Cascade

จดจำใบหน้าด้วย Siamese Neural Network

บันทึกข้อมูลการเข้าเรียนลงไฟล์ attendance.csv

รองรับการใช้งานผ่าน Web Application

ใช้โมเดลที่ฝึกไว้แล้ว (.pth / .pt)

🧠 Technologies Used

Python

OpenCV

PyTorch

Flask

NumPy / Pandas

Haar Cascade Classifier

Siamese Network

📂 Project Structure
Face-Recognition-Attendance/
│
├── app.py                         # ไฟล์หลักสำหรับรันเว็บแอป
├── model.py                       # โครงสร้างและการโหลดโมเดล AI
├── utils.py                       # ฟังก์ชันช่วยเหลือ (encode / compare face)
├── haarcascade_frontalface_default.xml
│
├── siamese_model.pth              # โมเดล Siamese Network
├── face_encoder.pt                # โมเดลแปลงใบหน้าเป็น feature
├── face_db.pt                     # ฐานข้อมูลใบหน้า
│
├── attendance.csv                 # ไฟล์บันทึกการเช็คชื่อ
│
├── templates/                     # HTML templates
├── static/                        # CSS / JS / Images
└── README.md

⚙️ Installation
1️⃣ Clone Repository
git clone https://github.com/Thizler/Face-Recognition-Attendance.git
cd Face-Recognition-Attendance

2️⃣ Install Dependencies
pip install -r requirements.txt


หากไม่มี requirements.txt แนะนำติดตั้ง:

pip install flask opencv-python torch torchvision numpy pandas

▶️ How to Run
python app.py


จากนั้นเปิดเบราว์เซอร์ไปที่:

http://127.0.0.1:5000

📝 Attendance Output

ข้อมูลการเช็คชื่อจะถูกบันทึกในไฟล์:

attendance.csv


รูปแบบข้อมูล:

Name	Date	Time
Student1	2025-01-01	08:30:15
🎯 Use Case

ระบบเช็คชื่อในห้องเรียน

ระบบยืนยันตัวตน

โปรเจคด้าน AI / Computer Vision

Mini Project / Final Project

🚀 Future Improvements

เชื่อมต่อฐานข้อมูล MySQL / Firebase

เพิ่มระบบ Login (Admin / Teacher)

รองรับหลายกล้อง

เพิ่มความแม่นยำของโมเดล

Deploy ขึ้น Cloud
