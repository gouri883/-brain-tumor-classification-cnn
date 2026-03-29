# 🧠 Brain Tumor Classification – Lab 3

A deep learning project that classifies brain tumor types (Glioma, etc.) from MRI images using a Convolutional Neural Network (CNN) built with TensorFlow/Keras.

## 📌 Objectives
- Load and preprocess MRI image data
- Apply image processing techniques (Gaussian Blur, Canny Edge Detection, Watershed Segmentation)
- Build and train a CNN model for multi-class classification
- Evaluate model performance using accuracy, confusion matrix, and ROC curves

## 🗂️ Dataset
Brain MRI images organized into Training and Testing folders by tumor type (e.g., Glioma).

## 🛠️ Tech Stack
- Python, TensorFlow/Keras
- OpenCV, PIL, Matplotlib
- Scikit-learn (metrics & evaluation)

## 🔬 Key Steps
1. Extract and load MRI images from ZIP archive
2. Visualize class distribution
3. Apply data augmentation (rotation, zoom, flip, etc.)
4. Preprocess with Gaussian Blur, edge detection, and segmentation
5. Train CNN with BatchNormalization, Dropout, and EarlyStopping
6. Evaluate with classification report, confusion matrix, and ROC-AUC curve

## 📊 Model Architecture
- Multiple Conv2D + MaxPooling2D layers
- BatchNormalization & Dropout for regularization
- GlobalAveragePooling2D → Dense → Softmax output

## 🚀 How to Run
1. Clone this repo
2. Place the dataset ZIP file in the root directory
3. Open `DV_lab3_.ipynb` in Jupyter Notebook or Google Colab
4. Run all cells in order
