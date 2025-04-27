# Human_Activity_Detection_Project
Human Activity Detection" (HAD) is a project where I build a system that can recognize what activity a person is doing — like walking, running, sitting, jumping, falling, etc. It's a popular topic in Machine learning, computer vision, and IoT. Depending on the project goal, there are different ways you can do it:
Here are the common types of HAD projects:

Video-based Detection

You use a camera to record people and apply computer vision models (like CNNs, 3D CNNs, or Transformers) to detect activities.

Datasets: UCF101, HMDB51, Kinetics.

Tools: OpenCV, TensorFlow, PyTorch, MediaPipe.

Sensor-based Detection

You use wearable sensors (accelerometer, gyroscope, etc.) — like in smartphones, smartwatches — and classify activities based on the motion signals.

Datasets: WISDM, PAMAP2, Opportunity Dataset.

Tools: Scikit-learn, TensorFlow, specialized hardware (Arduino, Raspberry Pi).

Pose-based Detection

You first extract human body keypoints (head, shoulders, elbows, knees, etc.) using pose estimation models (like OpenPose or MediaPipe Pose), and then analyze the poses over time to recognize activity.

Lightweight and works well even without full videos.

Typical pipeline:

Data collection → Data preprocessing → Feature extraction → Model training → Activity prediction → Evaluation.

Applications:

Health monitoring (e.g., fall detection for elderly)

Sports analytics

Security and surveillance

Human-computer interaction (like gesture control)



