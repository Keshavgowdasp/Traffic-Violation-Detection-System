🚦 Traffic Signal Violation Detection System using Computer Vision
<h3><a href="https://youtu.be/PxHkKLUk_QM" target="_blank">📺 Project Video Demonstration</a></h3> <h3><a href="https://drive.google.com/open?id=1H5RjHPJ0CK5yq2_3vwwo4CwZt1NXTeVB" target="_blank">📑 Project Report</a></h3> <h3><a href="https://drive.google.com/open?id=1l46H2pNTbLLcIFSHWsMtor-vlvNSA4Gu" target="_blank">📊 Project Slides</a></h3>

📌 Introduction

This project demonstrates a real-time traffic signal violation detection system built using Computer Vision, OpenCV, and YOLOv3 object detection.
The system detects vehicles, monitors traffic signal lines, and identifies violations when vehicles cross during a red light. It also provides a Tkinter-based GUI for user interaction and monitoring.

👉 If you just want to run it, jump to Quick Start
.

📂 Table of Contents

Motivation

Objectives

Quick Start

System Overview

Methodology

Implementation

Contributing

References

Author

License

💡 Motivation

With the rapid increase in vehicles worldwide, traffic violations have become a major cause of accidents and road congestion.
This project automates traffic rule enforcement by detecting signal violations in real-time, helping traffic police departments act quickly and efficiently.

🎯 Objectives

Detect and classify vehicles using YOLOv3 (Darknet-53).

Track vehicles and determine if a traffic line is crossed during red light.

Provide a real-time alert with bounding boxes (green → safe, red → violation).

Build a user-friendly GUI for monitoring and taking action.

🚀 Quick Start

Clone the repository:

git clone https://github.com/Keshavgowdasp/Traffic-Violation-Detection-System.git
cd Traffic-Violation-Detection-System


Update directories in Project-GUI.py and object_detection.py.

Download YOLOv3 weights from here
 if not included.

Install dependencies:

pip install -r requirements.txt


Run the project:

python Project-GUI.py

🔎 System Overview

Components:

Vehicle Detection Model (YOLOv3 + OpenCV)

Graphical User Interface (Tkinter)

Process:

Video footage is provided to the system.

Vehicles are detected and tracked.

A traffic line is drawn by the user.

If a vehicle crosses during red → violation is flagged.

GUI displays real-time results and generates output/output.mp4.

⚙️ Methodology
Vehicle Detection & Classification

Uses YOLOv3 object detection with Darknet-53.

Detects and classifies vehicles from live/recorded video.

Violation Detection

A line is drawn as the traffic signal line.

Vehicles crossing the line in red light state are flagged.

Bounding boxes change color:

✅ Green = No violation

❌ Red = Violation

🛠️ Implementation
Computer Vision

OpenCV for image processing.

TensorFlow + YOLOv3 for object detection.

Graphical User Interface

Tkinter GUI for:

Opening video files.

Drawing signal lines.

Displaying real-time violation detection.

🤝 Contributing

Contributions are welcome! 🚀

Fork the repository.

Create a feature branch.

Submit a pull request.

📚 References

YOLOv3 Paper

How to Perform Object Detection with YOLOv3

Research papers on real-time traffic violation detection.

👨‍💻 Author

Keshav Gowda S P
📧 keshavgowdasp@gmail.com

🔗 Portfolio

🔗 GitHub

📜 License

This project is licensed under the GNU GPLv3 License.
