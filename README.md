# visionBot

In this project, we utilize the laptop webcam to capture live video. This video is then processed to extract precise contours and color range. The object of interest, a red pen, is moved within a defined grid area. An object detection algorithm is employed to track the pen's position within the grid. This is done in OpenCV. When the pen is detected in a specific grid cell, the data is sent to an Arduino microcontroller. The microcontroller, in turn, controls the robot's movements, allowing it to go forward, backward, left, or right.
