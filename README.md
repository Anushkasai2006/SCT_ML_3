# 🦁🐘 Binary Image Classification - Lion vs Elephant

This project was completed as part of my internship at **SkillCraft Technology** under the Machine Learning domain. Instead of the standard Cat vs Dog classification, I chose to explore a more unique binary image classification problem — distinguishing between **lions** and **elephants** using a Convolutional Neural Network (CNN).

## 📌 Project Overview

The model is designed to classify images into two categories:
- **Lion**
- **Elephant**

It uses deep learning techniques to extract and learn important features from training images and generalize the classification on unseen test data.

## 🔧 Tools & Libraries Used

- Python
- TensorFlow / Keras
- CNN (Convolutional Neural Networks)
- OpenCV (for image preprocessing)
- NumPy, Matplotlib

## 🧠 Model Highlights

- Custom CNN architecture trained on lion and elephant datasets
- Data augmentation applied for improved generalization
- Achieved high validation accuracy
- Works well on test images

## 📁 Folder Structure

├── dataset/
│ ├── train/
│ │ ├── lion/
│ │ └── elephant/
│ └── test/
├── model/
│ └── binary_model.h5
├── train_model.py
├── test_model.py
├── predict_image.py
├── README.md
└── requirements.txt

bash
Copy
Edit

## 🚀 How to Run

1. **Clone the Repository**
```bash
git clone https://github.com/YourUsername/your-repo-name.git
cd your-repo-name
Install Required Libraries

bash
Copy
Edit
pip install -r requirements.txt
Train the Model

bash
Copy
Edit
python train_model.py
Test or Predict

bash
Copy
Edit
python predict_image.py
