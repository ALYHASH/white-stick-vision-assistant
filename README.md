
# White Stick Vision Assistant

An AI-powered wearable vision assistant designed to empower visually impaired individuals with real-time object detection, hazard alerts, OCR text recognition, and voice-activated interaction.

## 📌 Features
- 🎯 **Real-time Object Detection** using YOLOv8n
- 💵 **Currency Detection** for assisting visually impaired users with identifying banknotes
- ⚠️ **Hazard Detection** to warn about obstacles and dangerous objects
- 🗣️ **Voice Interaction** using Whisper for speech-to-text transcription
- 🖥️ **Optimized Embedded Code** for AMB82-MINI microcontroller
- ⚡ **Low-latency Design** suitable for wearable, battery-powered environments

## 🚀 Tech Stack
- **Languages:** Python 3.10, Embedded C (Arduino)
- **Libraries & Frameworks:** PyTorch, OpenCV, Whisper, YOLOv8n
- **Embedded System:** AMB82-MINI (ARM Cortex-M33)
- **Other Tools:** Tesseract (OCR), pvPorcupine (Wake Word Detection)

## 📂 Project Structure
```
white-stick-vision-assistant/
├── notebooks/          # Jupyter Notebooks for development and experiments
│   ├── currency_model.ipynb
│   ├── hazard_model.ipynb
│   └── main_code.ipynb
├── models/             # Pre-trained YOLO models (.pt files)
│   ├── currency.pt
│   └── hazard.pt
├── embedded_code/      # Embedded C code for AMB82-MINI
│   └── AMB82_Board_code.ino
├── requirements.txt    # Python dependencies
├── README.md           # This file
└── .gitignore          # Ignore large models and cache files
```

## ⚙️ Installation & Setup
1️⃣ **Clone the repository**
```bash
git clone https://github.com/ALYHASH/white-stick-vision-assistant.git
cd white-stick-vision-assistant
```

2️⃣ **Install dependencies**
```bash
pip install -r requirements.txt
```

3️⃣ **Run or explore the code**
- Open the notebooks in `/notebooks/` using Jupyter or VS Code.
- Upload `AMB82_Board_code.ino` to AMB82-MINI using Arduino IDE.

4️⃣ **Models**
- Pre-trained models are stored in `/models/`. Due to size, you may need to download models manually in the future.

## 📸 Demo
Coming Soon — Example usage and screenshots of the system in action.

## 📜 License
This project is licensed under the MIT License.

---

Built with ❤️ by [ALY HASSAN](https://github.com/ALYHASH)
