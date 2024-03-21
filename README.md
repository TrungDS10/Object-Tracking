# Object-Tracking

Overall pipeline:
![Screenshot 2024-03-21 at 15 15 03](https://github.com/TrungDS10/Object-Tracking/assets/72665487/dc5e16ff-5d22-4513-b7f3-7a99e7df3768)


In this project, we create a simple object tracking application using YOLOv8s for detector stage and DeepSORT for tracking phase:

- YOLO (You Only Look Once): is a fast and effective object detection model that allows identifying objects in an image or video by dividing the image into grids, predicting bounding boxes and class labels taking place on each. grid cell. YOLOv8 is the latest version with high accuracy and faster speed in different weather and lighting environments.
- DeepSORT (Simple Online and Realtime Tracking with a Deep Association Metric) is an object tracking algorithm based on a combination of deep learning and feature-based tracking techniques. It uses a siamese network to calculate similarity between consecutive bounding boxes in frames and tracks objects based on changes in this similarity.

When combining YOLOv8 and DeepSORT, we can effectively detect and track objects in videos. YOLOv8 will identify objects in each image frame, then DeepSORT will use this information to identify and track objects over time. The result is a complete system for tracking objects in video, which can be applied in many fields such as security surveillance, traffic monitoring, and many other applications that require location understanding and management location of objects in real time.

