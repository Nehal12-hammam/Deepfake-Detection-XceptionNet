# Deepfake Detection using XceptionNet

## 📌 Overview
A deep learning computer vision pipeline designed to detect manipulated and synthetic media (images and videos). The project leverages transfer learning by fine-tuning an XceptionNet architecture on the challenging Wild-Deepfake dataset to distinguish between authentic and forged facial content.

## 🛠️ Key Features & Pipeline
- **Data Preprocessing & Frame Extraction:** Utilizes OpenCV to extract, align, and normalize facial frames from video streams.
- **Model Architecture:** Fine-tuned XceptionNet (depthwise separable convolutions) optimized for capturing subtle spatial artifacts introduced during face manipulation.
- **Training & Evaluation:** Trained and benchmarked on the Wild-Deepfake dataset across diverse real-world lighting, compression, and manipulation scenarios.

## 💻 Technologies Used
- **Language:** Python
- **Deep Learning Frameworks:** PyTorch, TensorFlow
- **Architecture:** XceptionNet
- **Computer Vision:** OpenCV
