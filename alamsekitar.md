# 🟩 SLOT 3: APLIKASI IoT & OBJECT DETECTION DALAM PEMANTAUAN ALAM SEKITAR & SUMBER

📅 **2 Oktober 2025**  
🕚 **11:00 pagi – 1:00 tengah hari**  
🎙️ **Penceramah**: Prof. Madya Dr. Mohd Murtadha Mohamad  
👨‍🏫 **Fasilitator**: Prof. Madya Dr. Mohd Shahizan Othman  

**[slaid](https://github.com/drMurtadha/JKRIoTAI.md/blob/main/IoT_AI_Pantau_Alam_Sekitar.pdf)
---

## 🎯 Objektif Slot

- Memperkenalkan penggunaan **IoT berasaskan kamera & AI Object Detection** untuk pemantauan alam sekitar secara automatik dan berterusan  
- Memberi contoh penggunaan model seperti **YOLOv8**, **SSD**, dan **ResNet** dalam mengesan objek alam seperti **haiwan**, **sampah**, **pokok**, dan **kenderaan**  
- Menjelaskan **integrasi data dari kamera** dengan sistem pemantauan masa nyata (dashboard, alert system, cloud storage)  

---

## 🧭 Struktur Sesi

### 🔹 1. Pengenalan Ringkas
- Pengenalan IoT + Vision-based AI  
- Peranan kamera (CCTV, drone, edge device) dalam rangkaian IoT  
- Apa itu object detection (bukan sekadar image classification)  

### 🔹 2. Kenapa Object Detection untuk Alam Sekitar?
- Banyak objek perlu dikesan secara **visual**, bukan dengan sensor biasa  
- Pengenalpastian secara automatik: **haiwan terancam**, **pencemaran sungai**, **pembalakan haram**, **jentera berat**  
- Penting untuk **tindakan awal** dan **pengurusan sumber**  

---

## 🔍 Aplikasi Object Detection Berdasarkan Komponen Alam Sekitar

| Komponen         | Objektif Pengesanan                     | Contoh Objek                              | Model AI Disyorkan         |
|------------------|------------------------------------------|-------------------------------------------|-----------------------------|
| **Sungai**       | Pantau pencemaran, pembuangan sampah     | Botol plastik, buih, minyak               | YOLOv5 / YOLOv8             |
| **Hutan**        | Pantau pembalakan haram, jejak haiwan    | Gergaji rantai, lori, manusia, gajah      | YOLOv8m / SSD               |
| **Pantai**       | Kesan pencerobohan atau tumpahan         | Bot nelayan, drum tumpahan                | Faster R-CNN                |
| **Kawasan bandar**| Pemantauan longkang & banjir            | Sampah tersumbat, paras air tinggi        | YOLOv5 + ultrasonic sensor  |
| **Spesies liar** | Kenal pasti haiwan terancam              | Rusa, gajah, burung eksotik               | YOLOv8 + kamera trap        |

---

## ✅ Kajian Kes & Projek Nyata

### 📸 1. Smart River Surveillance with Object Detection
- Kamera CCTV + YOLOv8 untuk kesan pembuangan haram di sungai  
- Edge device (Raspberry Pi + Coral TPU) digunakan di kawasan terpencil  

### 🐘 2. Wildlife Monitoring System in Protected Forest
- Kamera trap dengan AI onboard (Jetson Nano + YOLO) mengesan harimau dan manusia  
- Notifikasi dihantar ke ranger melalui Telegram bot  

### 🌊 3. Drone-based Object Detection for Coastal Cleanup
- Drone dilengkapi kamera 4K  
- Objek dikenalpasti: plastik terapung, jaring, kayu besar  
- Koordinat dihantar ke pasukan lapangan melalui Google Maps API  

---

## 🛠️ Teknologi & Alat Disyorkan

- **Model AI**: YOLOv5, YOLOv8m, SSD, Faster R-CNN (trained via Roboflow / Ultralytics)  
- **Edge Device**: Raspberry Pi, Jetson Nano, Google Coral Dev Board  
- **Cloud Platform**: AWS Rekognition, Azure Custom Vision, HuggingFace Spaces  
- **Platform Visualisasi**: Streamlit, Power BI, Grafana  
- **Drone**: DJI Mavic Air 2 + RTMP Stream ke edge node  

---

## 🤖 Integrasi dengan IoT

- Kamera ➜ Stream video ➜ Edge AI ➜ Label objek ➜ Hantar data via MQTT ke cloud  
- Tambah sensor suhu, kelembapan, dan GPS ➜ gabung data untuk insight mendalam  
- Analitik lanjut: trend pembuangan sampah, heatmap haiwan, time-lapse deforestation  

---

## 🔬 Aktiviti / Demonstrasi (Cadangan)

- Demo mudah: gunakan webcam + YOLOv8 pre-trained model untuk kesan botol air dan manusia  
- Atau: paparkan video drone dan tunjuk bounding box hasil inference  

---

## 📚 Rujukan & Tutorial

- [YOLOv8 by Ultralytics](https://docs.ultralytics.com/)  
- [Roboflow Dataset for Environment Monitoring](https://universe.roboflow.com/)  
- [Tutorial: Object Detection with Jetson Nano](https://developer.nvidia.com/embedded/learn/jetson)  

---

## 🖥️ Demo Live Object Detection (Embedded)

### 1️⃣ YOLO Object Detection (Tensorflow.js)

## [demo1](https://shaqian.github.io/tfjs-yolo-demo/?utm_source=chatgpt.com)

> Gunakan kamera laptop / PC secara terus dengan model Tiny YOLO v1, v2, v3 & YOLOv3  

---

### 2️⃣ YOLOv9 Object Detection with Transformers.js

## [demo2](https://huggingface.co/spaces/Xenova/yolov9-web?utm_source=chatgpt.com)

> Upload imej atau gunakan contoh untuk uji YOLOv9 Object Detection  

---

## 🎤 Penutup

> “Dengan kamera dan model AI, bumi kini boleh ‘melihat’ sendiri. Tugas kita hanya membaca, memahami, dan bertindak.”
