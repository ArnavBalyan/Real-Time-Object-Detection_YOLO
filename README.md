# Real-Time-Object-Detection_YOLO
Real Time Object Detection using Darknet YOLO (You Only Look Once) algorithm, OpenCV on the COCO (Common Objects in Context) dataset.

## Implementation
Darknet YOLOv3 has been used to along with the YOLOv3 preconfigured weights to the sameple clip. The output clip is recieved at around 8 FPS.
### Increasing FPS 
Operations like fetching video from web camera are I/O intensive, we make use of threading (imutil.py) to make use of seperate thread for I/O related operations and end up in a heavily increased frame rate.
### Output
The output video is generated through OpenCV's VideoWriter to output_clip.mp4.
<br />
<br />
### Watch the video here:

[![Watch the video](https://img.youtube.com/vi/6vWMcXvH2Ro/0.jpg)](https://www.youtube.com/watch?v=6vWMcXvH2Ro)
