## Human Detection phase (Phase 1)
This is the stage 1 of our project, ie, real time violence detection alert system.

## YOUTUBE VIDEO FOR EXPLANATION
https://youtu.be/gJ_B291YuLo

## To set up:
1. Download the human detection.py file and upload it into a google colaboratory session, or just copy paste the entire code into the same.
2. Select GPU from the runtime session options in "Change Runtime Type" in "Runtime"
3. Upload the "testing video.mp4" into the home folder in the sidebar file upload options and download the Faster RCNN Inception V2 COCO Model from this link
http://download.tensorflow.org/models/object_detection/faster_rcnn_inception_v2_coco_2018_01_28.tar.gz
4. Upload the "frozen_inference_graph.pb" file into the home folder itself (same place where you uploaded the testing video)
5. Change ``cap = cv2.VideoCapture('/home/video.mp4')`` code into ``cap = cv2.VideoCapture('/home/testing video.mp4')``
6. Press the run button

## The colaboratory notebook we used (Dont Touch anything just view the code/output)
https://colab.research.google.com/drive/1eyoksqD_XhDUbiq1uMlspoEqw9LiWsvS?authuser=1

## The blog we used to implement this phase (Read for better understanding and better insight into steps)
https://medium.com/@madhawavidanapathirana/real-time-human-detection-in-computer-vision-part-2-c7eda27115c6
