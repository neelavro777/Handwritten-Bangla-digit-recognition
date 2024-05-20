# Introduction

Our project aims to develop a machine learning model capable of recognizing handwritten Bangla digits. By using machine learning techniques we learned in class, the goal is to create a robust system that accurately identifies Bangla numerical characters with high accuracy.

<div align="center">
    <img src="https://github.com/neelavro777/Handwritten-Bangla-digit-recognition/blob/main/.assets/Screenshot%202024-05-20%20141618.png" alt="Alt text">
</div>

# Problem Statement or Task Description

Bangla, being the fifth-most spoken language in the entire world with an unparalleled collection of literature, has been critically overlooked in terms of representation in the digital world. Recognizing Bangla digits poses unique challenges due to the script's diverse and complex shapes. This project aims to address this disparity by building an effective model specifically tailored for recognizing handwritten Bangla digits.

# Methodology

- **Data Collection**: Dataset of handwritten Bangla digits comprising various writing styles, sizes, and orientations from Kaggle.
  [Dataset link: https://www.kaggle.com/datasets/truthr/banglamnist]
- **Data Preprocessing**: We will use OpenCV for data preprocessing.
- **Model Selection**: Experiment with different machine learning algorithms (Neural Networks - NN, Convolutional Neural Networks - CNNs, Support Vector Machines - SVMs, Softmax Regression) to determine the most suitable for Bangla digit recognition.
- **Model Training and Evaluation**: Train the selected model on the dataset, fine-tune parameters, and calculate accuracy using test sets.

# Description of the Dataset

The dataset will consist of a collection of handwritten Bangla digit images. Each image will be grayscale and resized to a standardized format (e.g., 28x28 pixels) for consistency. The x values (Handwritten Digits) with corresponding y values (Digit Labels) are used to ensure supervised learning.

<div align="center">
    <img src="https://github.com/neelavro777/Handwritten-Bangla-digit-recognition/blob/main/.assets/Screenshot%202024-05-20%20142225.png" alt="Alt text">
</div>

# Required Technology

- **Programming Language**: Python
- **Machine Learning Frameworks**: TensorFlow, scikit-learn
- **Image Processing Libraries**: OpenCV (cv2)
- **Development Environment**: Google Colab / Jupyter Notebook
- **Libraries for Data Manipulation**: Pandas, NumPy

# Team members

- **Rafi Shahriyar**
- **Nafis Ashraf Roudra**
- **Neelavro Saha**
