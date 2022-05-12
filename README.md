# Real-Time-Violence-Detection
A real-time violence detector using `MobileNetV2` pretrained model and image enhancement algorithms and face detection algorithms implemented using Python, including an alert system built using telegram for alerting concerned authorities

## Stage 1 (Human Detection) ✔✔
A real-time human detector using `Faster RCNN Inception V2 COCO model`, implemented using Python. Main purpose was comparing 3 pretrained models for speed and accuracy.

## Stage 2 (Violence Detection) ✔✔
A real-time violence detector using `MobileNetV2` pretrained model, giving the output in the form of images with the result printed writen on each image using OpenCV, implemented using python. The training file for the mobilenetv2 model has also been included and the testing files and videos as well.

## Stage 3 (Alert System) ✔✔
Creating a telegram bot and a group, adding the bot to the group and whenever violence is detected in any frame, send the 30th `violence=true` frame to the telegram group using the bot, including a message which contains details like Location, Time and Camera ID
