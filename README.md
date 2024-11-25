# Invisible-Cloak-
Invisible Cloak using OpenCV in Python

#Problem Statement:  

Develop a real-time object detection and masking system that can seamlessly blend a specified object with its background, creating an illusion of invisibility to accurately detect and track the object and provide a user-friendly interface.

#Processing:

 Create a program that can detect a red cloth in a video feed from a webcam and replace the area covered by the cloth with the background, effectively making the person or object "disappear". The program must be able to:
•	Capture video feed from a webcam
•	Detect the red cloth in the video feed
•	Replace the area covered by the red cloth with the background
•	Display the output in real-time

#Overview:

OpenCV is a computer vision library that provides a wide range of functions for image and video processing. 

#Packages and Libraries Used:

The following packages and libraries are used in this project:

•	OpenCV (cv2) 

-pip install opencv -python

•	NumPy (numpy)

-pip install numpy

#Project Architecture

The "Invisible Cloak" project consists of the following steps:

•	Step 1: Capture Video Feed
 Capture video feed from a webcam. Initialize the webcam and set up the video capture pipeline.
 
•	Step 2: Convert to HSV 
Convert each frame to HSV colour space. Separate colour information from brightness information.

•	Step 3: Detect Red Colour 
Detect red colour in each frame. Identify pixels with red colour.

•	Step 4: Create Mask 
Create a mask for the red area. Invert the mask to get white pixels for red area.

•	Step 5: Replace with Background 
Replace red area with background. Perform bitwise AND operation with original frame and mask.

•	Step 6: Display Output
 It displays the output by Showing video feed with red colour "removed" in real-time.

 
