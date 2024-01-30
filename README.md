# HumanDetector

HumanDetector is a versatile Python-based tool for real-time human detection and counting using the Faster R-CNN Inception v2 model. It empowers users to effortlessly analyze images, videos, and camera feeds for human presence. Whether for surveillance, crowd monitoring, or any other application, HumanDetector has you covered.

![Human Detection](https://github.com/footcricket05/HumanDetector/blob/main/Screenshots/1.jpg)

## Features

- **Real-time Detection:** HumanDetector provides real-time human detection and counting capabilities for images, videos, and live camera feeds.

- **Easy-to-Use Interface:** The user-friendly graphical interface makes it simple for users to select and process their desired media.

- **Enumeration Plot:** Visualize human counts over time with the Enumeration Plot feature.

- **Avg. Accuracy Plot:** Monitor average accuracy with the Avg. Accuracy Plot, offering insights into the detection process.

- **Crowd Report Generation:** Generate detailed crowd reports in PDF format, including essential statistics and crowd status.

## Requirements

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

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/footcricket05/HumanDetector.git
   cd HumanDetector
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python main.py
   ```

4. Use the application to detect and count humans in your images, videos, or camera feeds.

## Usage

1. Launch the application using `main.py`.

2. Select one of the following options:
   - **DETECT FROM IMAGE:** Choose an image file and click `SELECT` to process it.
   - **DETECT FROM VIDEO:** Select a video file and click `SELECT` to analyze it.
   - **DETECT FROM CAMERA:** Click `OPEN CAMERA` to start real-time detection from your camera feed.

3. After processing, the application will display an Enumeration Plot and Avg. Accuracy Plot.

4. To generate a crowd report, click the `Generate Crowd Report` button.

## Start Page



## Contributors

We appreciate contributions to improve this project! If you'd like to contribute, please check out the [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
