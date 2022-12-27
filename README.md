# fatigue-detection
Keras and openCV Fatigue Detection 

First, you will need to capture video from a camera mounted in the car, or from a video file. You can use OpenCV's cv2.VideoCapture function to do this.

Next, you will need to pre-process the video frames to prepare them for analysis. This can include cropping the frame to focus on the driver's face, converting the frame to grayscale, and possibly applying other image processing techniques such as smoothing or histogram equalization.

Once you have pre-processed the video frames, you will need to extract features from them that can be used to identify fatigue. Some possible features you could extract include the driver's eye state (open or closed), the driver's head position (tilted or upright), and the driver's facial expression (smiling or neutral).

With the extracted features, you can now train a machine learning model to classify the driver's fatigue level. Keras is a popular library for building and training deep learning models, so you could use that to build and train a model to classify the driver's fatigue level.

Finally, you will need to implement a system for alerting the driver when fatigue is detected. This could involve displaying a warning message on the screen, sounding an alarm, or taking some other action to alert the driver.
