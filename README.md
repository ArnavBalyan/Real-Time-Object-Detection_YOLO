# Real-Time-Object-Detection_YOLO
Real Time Object Detection using Darknet YOLO (You Only Look Once) algorithm, OpenCV on the COCO (Common Objects in Context) dataset.

## Implementation
Darknet YOLOv3 has been used to along with the YOLOv3 preconfigured weights to the sameple clip. We get output clip is recieved at around 8 FPS.
### Increasing FPS 
Operations like fetching video from web camera are I/O intensive, we make use of threading (imutil.py) to make use of seperate thread for I/O related operations and end up in a heavily increased frame rate.
### Output
The output video is generated through OpenCV's VideoWriter to outpu_clip.mp4.

[![Watch the video](https://img.youtube.com/vi/AWNhLxG521w/0.jpg)](https://youtu.be/AWNhLxG521w)
