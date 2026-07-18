# 🧠 Brain Tumor MRI Classification using Machine Learning

**Project Image**

---

# 📌 Overview

This project builds an end-to-end computer vision and machine learning pipeline for multiclass brain tumor classification using MRI images.

The project demonstrates a complete image classification workflow, including image preprocessing, image-to-tabular data conversion, feature scaling, dimensionality reduction using Principal Component Analysis (PCA), model training, and performance evaluation using a Support Vector Machine (SVM) classifier.

---

# 📂 Dataset

**Source:** Kaggle – Brain Tumor MRI Dataset

https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

The dataset consists of labeled brain MRI images organized into separate training and testing folders.

The dataset contains MRI images belonging to four classes:

- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

During preprocessing, all MRI images were converted to grayscale, resized to a fixed resolution, flattened into feature vectors, and converted into a tabular dataset suitable for classical machine learning algorithms.

### Target Variable

**Label → Tumor Type**

---

# 🎯 Objective

The objective of this project is to build a machine learning model capable of accurately classifying brain MRI images into their respective tumor categories using computer vision preprocessing, Principal Component Analysis (PCA), and Support Vector Machine (SVM).

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- OpenCV (cv2)
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📊 Project Workflow

The project follows an end-to-end machine learning workflow:

- Image Dataset Loading
- Image Preprocessing
- Image-to-CSV Conversion
- Data Inspection
- Feature Scaling using StandardScaler
- Principal Component Analysis (PCA)
- Label Encoding
- Model Training
- Model Evaluation

---

# 🖼️ Image Preprocessing

The following preprocessing steps were performed:

- Loaded MRI images from the dataset folders
- Converted images to grayscale
- Resized all images to a fixed resolution
- Flattened each image into a one-dimensional feature vector
- Converted the image dataset into CSV format
- Created separate training and testing datasets

---

# 🔍 Data Preprocessing

The following preprocessing steps were applied before model training:

- Loaded the generated training and testing datasets
- Separated features and target labels
- Encoded class labels using LabelEncoder
- Standardized pixel values using StandardScaler
- Applied Principal Component Analysis (PCA) for dimensionality reduction
- Prevented data leakage by fitting preprocessing steps only on the training data

---

# 🤖 Machine Learning Model

The following classification algorithm was trained and evaluated:

- Support Vector Machine (SVM)

---

# 📈 Model Evaluation

The model was evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

The performance metrics provide insight into the classifier's ability to distinguish between the four brain tumor categories.

---

# ✅ Results

- Built a complete computer vision and machine learning pipeline for brain MRI image classification.
- Converted raw MRI images into a structured tabular dataset suitable for classical machine learning.
- Applied feature scaling and Principal Component Analysis (PCA) to reduce data dimensionality.
- Successfully trained an SVM classifier for multiclass brain tumor classification.
- Evaluated the model using accuracy, classification report, and confusion matrix.

---

