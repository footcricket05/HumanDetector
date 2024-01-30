# ✔️ HumanDetector: Real-Time Human Detection & Counting

A TensorFlow-based Faster R-CNN Inception v2 Python model for real-time human detection and counting in images, videos, and live camera feeds.

📌 **Requirements:**
- Python 3
- tkinter
- messagebox
- PIL
- cv2
- argparse
- matplotlib.pyplot
- numpy
- time
- os
- tensorflow
- fpdf

## 🚀 How this Script Works:

1. Download the code and run `main.py` on your local system.
2. The initial window of the application displays options to START or EXIT.
3. Click START to access the main functionality.
4. Choose from three options: DETECT FROM IMAGE, DETECT FROM VIDEO, or DETECT FROM CAMERA.
5. For image and video detection, select the respective files using the SELECT button.
6. Preview the selected file with the PREVIEW button, then detect and count humans with the DETECT button.
7. For camera detection, click OPEN CAMERA to start real-time detection.
8. After the detection process completes or is manually stopped, two plots are generated:
   - Enumeration Plot (Human Count vs. Time)
   - Avg. Accuracy Plot (Average Accuracy vs. Time).
9. You can also generate a crowd report in PDF format, which includes information such as Max Human Count, Max Accuracy, Max Avg. Accuracy, and a two-line crowd status.

## 📋 Purpose:

This script simplifies real-time human detection and counting in images, videos, and live camera feeds. It also provides crowd analysis through a generated crowd report.

## ⚙️ Compilation Steps:

1. Install the required libraries.
2. Download the code.
3. Run `main.py` on your local system.
4. Explore the application and perform human detection and counting.

## 📷 Screenshots:

**Image Detection:**

![Image 1](Screenshots/3.jpg)
![Image 2](Screenshots/4.jpg)
![Image 3](Screenshots/5.jpg)

**Video Detection:**

![Video 1](Screenshots/13.jpg)
![Video 2](Screenshots/14.jpg)
![Video 3](Screenshots/15.jpg)

**Camera Detection:**

![Camera 1](Screenshots/18.jpg)
![Camera 2](Screenshots/19.jpg)
![Camera 3](Screenshots/20.jpg)


