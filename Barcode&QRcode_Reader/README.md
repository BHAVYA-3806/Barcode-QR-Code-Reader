# 📷 Barcode & QR Code Reader using Python

This project is a real-time **Barcode and QR Code Scanner** built with Python using **OpenCV** and **pyzbar**. It reads barcodes and QR codes through a webcam and displays decoded information on-screen and saves it in a text file.

---

## 🚀 Why I Built This Project

It started with a simple observation: everywhere I looked — from café tables and delivery boxes to event passes — QR and barcodes were silently doing their job, enabling fast, contactless, and error-free communication. I was curious about the tech behind it.

So, I built this project to explore how machines read these codes in real time. It’s a compact yet powerful scanner using Python that decodes QR and barcodes through a webcam — simulating the core of what powers retail checkouts, inventory systems, and digital menus today. It’s fast, reliable, and a great entry point into the world of computer vision.

This project allowed me to:
- Learn and apply **OpenCV for video capture and drawing**
- Use **pyzbar** for barcode/QR code decoding
- Understand the flow of **real-time image processing**
- Create something practical and easily extendable (e.g., for inventory systems, attendance tracking, etc.)

---

## 🛠️ Tech Stack

- **Python 3.x**
- **OpenCV** – for capturing and processing frames
- **pyzbar** – for decoding barcodes and QR codes
- (Optional) **Pillow** – for handling static image input (not used in this version)

---

## 🧠 Features

✅ Reads barcodes and QR codes from webcam  
✅ Displays decoded data directly on the video frame  
✅ Saves the decoded result to `barcode_result.txt`  
✅ Real-time processing with minimal latency  
✅ ESC key to exit the scanning loop

---

## 🔧 Installation

### 1. Clone the repository

```
git clone https://github.com/yourusername/barcode-qr-reader.git
cd barcode-qr-reader
```

### 2. Install dependencies

```
pip install opencv-python pyzbar Pillow
```
---

### ▶️ How to Run

```
python bar.py
```
Once the webcam opens:

- 📷 Show a **barcode or QR code** to the camera.
- 🖥️ The **decoded data** will be displayed on the screen.
- 💾 It will also be **saved to `barcode_result.txt`**.
- ⎋ Press **ESC** to exit the scanner.

---

### 🛠️ Possible Extensions

- 🖼️ Add a **GUI interface** using Tkinter or PyQt for better usability  
- 🧾 **Log history** of all scanned codes with timestamps  
- 🔔 Play a **sound or alert** on successful scan  
- 🖼️ Support **batch scanning** from saved image files  
- 💻 Convert the script into a **standalone `.exe`** using PyInstaller for easy distribution  

---

### 💡 Applications

- 📦 **Inventory Management** – Scan products for real-time stock updates  
- 🎫 **Event Check-ins** – QR-based entry for attendees  
- 💳 **Contactless Payments** – Decode payment QR codes quickly  
- 📚 **Library Systems** – Manage book lending using barcode scans  
- 🕒 **Attendance Tracking** – Log user presence using personal QR codes  
- 🏷️ **Smart Product Tagging** – Attach scannable codes to physical items  

---

### 📬 Author

**BHAVYA**  
GitHub: [@BHAVYA-3806](https://github.com/BHAVYA-3806)  

---

### 📜 License

This project is open-source and available under the **MIT License**.  
Feel free to use, modify, and distribute it as per the license terms.

---