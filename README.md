# python-opencv-text-detection
A demo app for text detection using python opencv and tensorflow

# Running this application
Download and install Python
Download and install pip
Run pip install cv2, numpy

Once done run the command:- python text_detection.py --image images/lebron_james.jpg --east frozen_east_text_detection.pb
The above will detect text on the input image

For text detection in video stream run the below command

 python text_detection_video.py --east frozen_east_text_detection.pb
 The above command will start the video stream using your camera and any text you bring up will be identified.
