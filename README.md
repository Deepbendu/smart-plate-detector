
# 🔍 Smart Number Plate Recognition using OpenCV & OCR

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.20-orange.svg)](https://streamlit.io/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.5.1-brightgreen.svg)](https://opencv.org/)
[![Status](https://img.shields.io/badge/status-active-brightgreen.svg)]()

## Overview  
This project streamlines vehicle identification by automatically detecting number plates, extracting the text via OCR, and identifying the vehicle's state of registration. Leveraging Haar Cascade for detection, EasyOCR for text recognition, and a sleek Streamlit interface, it delivers an intuitive and real-time experience.

---

## Features  
- **Real-Time Detection**: Rapidly detects number plates in images and video streams.  
- **Accurate Text Recognition**: Utilizes EasyOCR to extract plate text precisely.  
- **State Identification**: Maps recognized text to Indian state codes to determine vehicle origin.  
- **User-Friendly GUI**: A clean Streamlit app lets users easily upload files and view results instantly.  
- **Scalable Architecture**: Designed for future enhancements like multilingual OCR or centralized vehicle databases.

---

## Technology Stack  
- **Programming Language:** Python  
- **Libraries:** OpenCV, EasyOCR, Streamlit  
- **Detection Technique:** Haar Cascade Classifier  

---

## How It Works  
1. **Input**: Upload images or videos through the app interface.  
2. **Detection**: Detect number plates in frames using Haar Cascade.  
3. **OCR**: Extract text from detected plates using EasyOCR.  
4. **Mapping**: Identify the vehicle's state by matching the extracted text with state codes.  
5. **Display**: Show the number plate, extracted text, and state on the GUI.

---

## Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Deepbendu/smart-plate-detector.git
   ```  
2. Navigate to the project directory:  
   ```bash
   cd vehicle-number-plate-detection
   ```  
3. Install the required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
4. Run the Streamlit app:  
   ```bash
   streamlit run app.py
   ```  
5. Upload your video or image through the app interface and watch the magic happen!  

---

## Output Preview

![Screenshot 2024-12-06 072800](https://github.com/user-attachments/assets/d268d446-b853-4974-9c50-752d59c64570)

---

## 🙋‍♂️ About Me

**Deepbendu Debnath**  
Full Stack Developer | AWS Certified SA | C++ Problem Solver  
Made with ❤️ in India 🇮🇳

---

## 📬 Contact

I'm always open to connect for internships, full-time roles, mentorship, or collaborative projects:

✉️ debnathdeepbendu@gmail.com  
💼 [LinkedIn](http://linkedin.com/in/deepbendu-debnath) | 📁 [GitHub](https://github.com/Deepbendu) | 🧩 [LeetCode](https://leetcode.com/deepbendu)

