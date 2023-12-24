# Pedestrian-and-Car-Detection

OpenCV Car and Pedestrian Detection
This project utilizes OpenCV and the Haar Cascade algorithm to perform real-time detection of cars and pedestrians in images or video streams. The Haar Cascade classifier is a machine learning object detection method used to identify objects in images or video.

# Table of Contents
#Introduction
#Requirements
#Installation
#Usage
#Examples
#Contributing
# Introduction
This project provides a simple and efficient solution for detecting cars and pedestrians using OpenCV's implementation of the Haar Cascade algorithm. It's suitable for applications such as traffic monitoring, surveillance, and more.

# Requirements

Python 3.x

OpenCV

NumPy

# Installation

Clone the repository:

bash
Copy code
git clone https://github.com/SWagaTo777/opencv-car-pedestrian-detection.git
Change into the project directory:

bash
Copy code
cd opencv-car-pedestrian-detection
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Run the car_pedestrian_detection.py script to start the detection on a video file or webcam feed. Customize the script parameters to suit your needs.

bash
Copy code
python car_pedestrian_detection.py --video path/to/your/video.mp4
You can also use the --image flag to perform detection on a single image:

bash
Copy code
python car_pedestrian_detection.py --image path/to/your/image.jpg
For additional options and details, run:

bash
Copy code
python car_pedestrian_detection.py --help
Examples
Video Detection
bash
Copy code
python car_pedestrian_detection.py --video path/to/your/video.mp4
Image Detection
bash
Copy code
python car_pedestrian_detection.py --image path/to/your/image.jpg
Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

Fork the repository.

Create a new branch: git checkout -b feature/my-feature.

# License

This project is licensed under the MIT License.
