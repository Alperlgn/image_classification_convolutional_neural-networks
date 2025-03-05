# 🖼️ Image Classification: Categorizing Products with  (CNN)

This project aims to **analyze product images and determine their respective categories**. Using a **Convolutional Neural Network (CNN)**, the classification of images into different product categories was performed.

**Dataset:** The dataset consists of images from three different categories:

- **All Beauty**: Beauty product images
- **Digital Music**: Digital music album covers
- **Health and Personal Care**: Health and personal care product images

The dataset was cleaned, missing images were filtered, and training/test datasets were prepared.

---

## 🔍 Data Preprocessing

### 📌 Image Processing and Cleaning

- **Identified and removed missing or corrupted images.**
- **Normalized images** (converted pixel values to a 0-1 range).
- **Resized all images to 224x224 pixels** for consistency.

### 🏗️ Training and Test Datasets

- **Selected 15,000 samples from each category.**
- **Split data into 80% training and 20% testing sets.**

---

## 🤖 Modeling and Performance Evaluation

### 📊 Model Used

- **Convolutional Neural Network (CNN)**

### 📈 Model Performance Analysis

| Epoch | Training Accuracy | Test Accuracy |
| ----- | ----------------- | ------------- |
| 1     | 56.2%             | 69.6%         |
| 5     | 82.5%             | 78.3%         |
| 10    | 91.1%             | 78.3%         |

- **The model achieved 91% accuracy on the training set but 78% on the test set.**
- **Confusion Matrix analysis** was conducted to evaluate classification errors.

---

## 🛠️ Technologies Used

- **Python (Pandas, NumPy, TensorFlow/Keras)**
- **Data Visualization (Matplotlib, Seaborn)**
- **Image Processing (PIL, OpenCV)**
- **Deep Learning & CNN-based Models**

---

## 📊 Visualization

- **Confusion Matrix** was used to analyze classification errors.
- **Category-wise accuracy** was calculated to assess model performance.

### 🚀 Key Insights

- **CNN performed well in classifying images into different categories.**
- **Data imbalance and similar image features caused some classification errors.**
- **Techniques such as Transfer Learning could further improve model performance.**

---

This project serves as a great reference for those interested in **computer vision and deep learning for image classification**. Open to feedback and discussions! 🚀

