# Skin Cancer Malignant Classification

This project focuses on building a deep learning model to classify skin cancer images into malignant or benign categories. The model leverages the power of transfer learning by utilizing the ResNet50 architecture.

## 🛠 Technologies Used
- Python
- TensorFlow
- Keras
- ResNet50 (Pretrained on ImageNet)

## 📚 Project Steps
1. **Data Loading:** Imported and prepared the dataset of skin cancer images.
2. **Preprocessing:** Resized images and normalized pixel values.
3. **Model Building:** Used ResNet50 with transfer learning:
   - Removed the top layer.
   - Added new fully connected layers suitable for binary classification.
4. **Training:** Trained the model using TensorFlow and Keras APIs.
5. **Evaluation:** Evaluated the model's performance on test data and analyzed results.
6. **Prediction:** Tested the model with new images.

## 🎯 Objective
To create an accurate, efficient, and reliable model that helps in the early detection of malignant skin cancer using deep learning techniques.

## 🚀 How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/skin-cancer-malignant-classification.git
    ```
2. Install the required libraries:
    ```bash
    pip install tensorflow keras matplotlib numpy
    ```
3. Run the notebook:
    Open `skin_cancer_malignant.ipynb` in Jupyter Notebook or any IDE that supports `.ipynb` files.

## 📈 Results
- Achieved good accuracy during training and testing phases.
- The model can differentiate between malignant and benign skin cancer images effectively.

## 🤝 Contribution
Feel free to fork the repository and submit pull requests if you want to contribute!


