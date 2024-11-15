# PoseEstimation
This project is dedicated to evaluating and comparing leading human pose estimation algorithms, including HRNet, AlphaPose, PoseNet, and MediaPipe. The aim is to provide a comprehensive analysis of their performance in terms of accuracy, efficiency, and reliability for real-world applications such as motion analysis, sports, healthcare, and AR/VR.
## Key Features
Algorithm Integration: Implements state-of-the-art pose estimation models for a detailed comparative study.
Evaluation Metrics: Assesses performance using PCK (Percentage of Correct Keypoints), OKS (Object Keypoint Similarity), FPS (Frames Per Second), FPR (False Positive Rate), and FNR (False Negative Rate).
Dataset Support: Built to work seamlessly with the COCO dataset for standardized benchmarking.
Visualization Tools: Provides intuitive visual overlays of detected keypoints on input images for error analysis and validation.
## Project Workflow
Load the COCO validation dataset.
Perform pose estimation using each algorithm.
Evaluate predictions against ground truth using well-defined metrics.
Compare results across multiple dimensions, including accuracy, computational efficiency, and error rates.
