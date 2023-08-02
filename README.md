# Motion_Detection

## I recently built a motion detection project using OpenCV, a popular computer vision library. This project can detect both human presence and general motion in real-time using a webcam.

## The project works by first loading a pre-trained person detection model. This model is based on the Haar feature-based cascade classifiers and can detect full-body humans.

## Next, the project initializes variables for motion detection, including the previous frame and a flag for motion detection.

## Then, the project opens the default camera and starts a loop to continuously read frames from the camera. For each frame, the project compares it to the previous frame and calculates the difference between the two frames. If the difference is greater than a certain threshold, then the project determines that there has been motion.


