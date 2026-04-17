# LUNG-CANCER-DETECTION-USING-CNN
📌 Overview

This project focuses on detecting lung cancer from CT scan images using a Convolutional Neural Network (CNN). The model is trained to classify images into cancerous and non-cancerous categories, helping in early diagnosis and improving decision-making in healthcare.

🎯 Objectives
Build a deep learning model for lung cancer detection
Perform image preprocessing and augmentation
Achieve high accuracy in classification
Provide a simple interface for predictions
🛠️ Tech Stack
Programming Language: Python
Libraries: TensorFlow, Keras, OpenCV, NumPy, Pandas, Matplotlib
Tools: Jupyter Notebook, Streamlit (for UI), Git
📂 Project Structure
lung-cancer-detection-cnn/
│── dataset/              # (Not uploaded due to size)
│── model/                # Saved trained model
│── train.py              # Model training script
│── app.py                # Streamlit app for prediction
│── requirements.txt      # Dependencies
│── README.md             # Project documentation
│── .gitignore            # Ignored files
⚙️ Methodology
1. Data Preprocessing
Image resizing and normalization
Noise reduction using OpenCV
Data augmentation (rotation, flipping)
2. Model Architecture
Convolutional Layers (feature extraction)
Max Pooling Layers (dimensionality reduction)
Fully Connected Layers (classification)
Activation Function: ReLU, Softmax
3. Training
Loss Function: Categorical Crossentropy
Optimizer: Adam
Evaluation Metrics: Accuracy
📊 Results
Achieved 96–98% accuracy on test dataset
Model successfully distinguishes between cancerous and non-cancerous images
