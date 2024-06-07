## OpenCV Face Detection Project
This project demonstrates face detection using OpenCV's Haar Cascade classifier. The classifier used is haarcascade_frontalface_default.xml, which is specifically trained to detect frontal faces in images.


## Introduction
Face detection is a computer vision task that identifies and locates human faces in digital images. This project uses OpenCV, an open-source computer vision library, to perform face detection. The haarcascade_frontalface_default.xml file is a pre-trained model provided by OpenCV that detects frontal faces using the Haar feature-based cascade classifier technique.

## Installation
To run this project, you need to have Python and OpenCV installed. You can install the necessary dependencies using pip:

pip install opencv-python
You will also need to download the haarcascade_frontalface_default.xml file, which is available in the OpenCV GitHub repository or directly from your OpenCV installation path.
Ensure you have the haarcascade_frontalface_default.xml file in your project directory. If not, you can download it from here.

Run the face detection script:

python face_detection.py
The script will process the images or video stream and display the detected faces.
 **Video Reference**: The `[![Play Lane](videos/play_lane.mp4)](https://github.com/MissNeerajSharma/Open-CV/blob/master/lanes_clip.mp4)
## License
This project is licensed under the MIT License. See the LICENSE file for details.
