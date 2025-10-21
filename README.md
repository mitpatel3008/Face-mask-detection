🩺 Face Mask Detection using CNN

📘 Overview

This project implements a deep learning model to detect whether a person is wearing a face mask or not using Convolutional Neural Networks (CNNs). The model performs binary image classification on a dataset of over 7,500 labeled images.

⸻

⚙️ Features
	•	Real-time face mask detection using a trained CNN model.
	•	Robust preprocessing pipeline for image resizing and normalization.
	•	High accuracy achieved through optimized architecture and dropout regularization.

⸻

🧠 Model Architecture

The CNN is implemented using TensorFlow/Keras and consists of:
	•	Conv2D and MaxPooling2D layers for feature extraction.
	•	Dropout layers to reduce overfitting.
	•	Dense (Fully Connected) layers for final binary classification.

⸻

🧩 Dataset
	•	Contains 7,500+ images categorized as Mask and No Mask.
	•	Images resized to 128×128 pixels and normalized for consistent training.
	•	Data split into training (80%) and validation (20%) sets.

⸻

🚀 Training Details
	•	Loss Function: Binary Cross-Entropy
	•	Optimizer: Adam
	•	Batch Size: 32
	•	Epochs: 20
	•	Dropout Rate: 0.2
	•	Achieved strong validation accuracy for reliable real-world performance.

⸻

🛠️ Technologies Used
	•	Python
	•	TensorFlow / Keras
	•	OpenCV
	•	NumPy, Pandas, Scikit-learn
	•	Matplotlib, Seaborn
