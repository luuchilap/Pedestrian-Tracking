-Combining YOLOv8 and DeepSORT to create a robust pedestrian tracking system capable of processing video frames in real-time, identifying, and tracking the movement of individuals across various frames. This model can be applied to security surveillance camera and traffic monitoring.

-Dataset: The project uses the MOT17 dataset (Multiple Object Tracking 17), which contains multiple videos converted into image frames, categorized into training and testing sets.

- Detector Module: Uses YOLOv8 for detecting pedestrians in each video frame.

-Tracker Module: Employs DeepSORT to track the detected pedestrians' trajectories across frames.
