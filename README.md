# 🧠 Face Recognition-Based Smart Attendance System

A Python desktop application using `face_recognition`, `OpenCV`, and `Tkinter` for smart attendance management via webcam and images.

## 📌 Features

- ✅ Face recognition with real-time webcam capture
- 🧠 Preloading face encodings with progress feedback
- 🔎 Search and select user to simulate presence
- 📷 Manual image insertion and recognition
- 🎲 Random face selection for testing
- 🗂 Attendance logging with timestamps (CSV)
- 💾 Encoding cache for faster future loads

---

## 🛠️ Tech Stack

- **Language**: Python 3.x  
- **Libraries**: 
  - `face_recognition`
  - `OpenCV`
  - `Tkinter`
  - `Pillow`
  - `pandas`
  - `numpy`

---

## 📂 Project Structure
📁 archive (2) ├── 📁 Faces │ └── Faces/ # Cropped face images ├── 📁 Original Images │ └── Original Images/ # Full original images per person ├── 📁 Inserted Images/ # Manually inserted images ├── Dataset.csv # Mapping of image ID to label ├── attendance.csv # Output attendance logs ├── face_encodings.pkl # Cached encodings (auto-generated) └── temp_capture.jpg # Temporary webcam capture

## 🚀 How to Run

1. **Install dependencies** (you can use `pip install -r requirements.txt`):

    ```bash
    pip install face_recognition opencv-python pillow pandas numpy
    ```

2. **Ensure directory structure and CSVs are set correctly** inside `archive (2)`.

3. **Run the project**:

    ```bash
    python main.py
    ```

4. **Choose mode**:
    - Simulated webcam mode with image interaction
    - Real webcam mode (captures once and recognizes)

---

## 📋 Attendance Output

Attendance logs are saved as:

```csv
Name,Timestamp
Alice,2025-04-17 10:15:22
Bob,2025-04-17 10:16:03
🧠 Future Improvements
Continuous webcam streaming for real-time attendance

GUI enhancements (dark mode, dashboard view)

Face addition/updating system

Exporting logs to Excel/PDF

Email alerts on unknown detection

📄 License
This project is licensed under the MIT License.

🙋‍♀️ Author
Sandhya Sharma
📧 sandhya24102001@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/sandhya-sharma-24oct2004/




