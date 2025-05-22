# AI Smart Lock with Raspberry Pi and TensorFlow

This project aims to create a secure facial recognition-based smart lock system using a Raspberry Pi, camera, and electromagnetic lock.

## 📌 Objective
Use facial recognition to unlock a door automatically if an authorized face is detected.

## 💡 Key Components
- Raspberry Pi 4
- Electromagnetic Lock (12V)
- Relay Module
- Pi Camera or USB Webcam
- Python, OpenCV, face_recognition, TensorFlow (optional for future improvements)

## 📈 Workflow (See Flowchart)
1. System captures video feed from camera
2. Face is detected and encoded
3. If it matches stored encoding:
   - Unlock relay (trigger GPIO pin)
4. Else:
   - Stay locked and log attempt

## 🔧 Status
> ⚙️ Planning and initial setup in progress. Hardware pending delivery.

## ✅ To Do
- [ ] Write initial face recognition script
- [ ] Finalize wiring diagram
- [ ] Train and store known face encodings
- [ ] GPIO trigger to lock/unlock
- [ ] Test on hardware
- [ ] (Optional) Dockerize for deployment
