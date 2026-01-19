Project Overview:
Emotion recognition is an important area of research in human–computer interaction, where machines are trained to detect and interpret human emotions based on facial expressions. This project focuses on developing a **Deep Learning–based Facial Emotion Recognition (FER) system** using **Convolutional Neural Networks (CNNs)**.

The system is designed to automatically classify facial images into different emotional categories by learning discriminative facial features from image data. Multiple CNN architectures are studied, implemented, and evaluated using standard facial emotion datasets.


🎯 Objectives
- To study and understand facial emotion recognition techniques
- To implement CNN-based deep learning models for emotion classification
- To compare the performance of different CNN architectures
- To evaluate models using benchmark datasets such as FER2013, JAFFE, and CK+



🧠 Models Used
The following CNN architectures were analyzed and implemented in this project:

- **ResNet-50**
- **VGG-16**
- **AlexNet**
- **GoogleNet (Inception)**

Each model was trained and evaluated to analyze its ability to recognize facial emotions from images.



🛠️ Technologies Used
- **Programming Language:** Python  
- **Deep Learning Frameworks:** TensorFlow, Keras  
- **Libraries:** NumPy, Pandas, Matplotlib, Scikit-learn  
- **Environment:** Jupyter Notebook  



📊 Datasets Used

### 🔹 FER2013 Dataset
- Grayscale facial images of size **48 × 48**
- Total images: **35,887**
- Emotion classes:
  - Angry
  - Disgust
  - Fear
  - Happy
  - Sad
  - Surprise
  - Neutral

### 🔹 JAFFE Dataset
- 213 grayscale images of Japanese female subjects
- 7 emotion categories
- Resolution: **256 × 256**

### 🔹 CK+ Dataset
- 593 video sequences from 123 subjects
- Includes labeled peak expressions
- Widely used for facial expression analysis

🔄 Methodology

### 1️⃣ Data Preprocessing
- Dataset cleaning and normalization
- Conversion of pixel values into image arrays
- Image resizing and formatting
- Splitting datasets into training and validation sets

### 2️⃣ Face Detection and Feature Learning
- CNN models automatically extract spatial features from facial images
- No manual feature extraction required

### 3️⃣ Model Training
- Models trained using labeled emotion data
- Activation functions: ReLU and Softmax
- Optimization performed using backpropagation

### 4️⃣ Emotion Classification
- Final classification performed using fully connected layers
- Output represents probability distribution over emotion classes



📈 Results

### 🔹 ResNet-50
- **FER2013 Accuracy:** 85.80%
- **JAFFE Accuracy:** 85.71%

### 🔹 VGG-16
- **FER2013 Accuracy:** 85.85%
- **JAFFE Accuracy:** 85.71%

### 🔹 AlexNet
- **FER2013 Accuracy:** 60.85%
- **JAFFE Accuracy:** 68.59%

The results demonstrate that deeper architectures such as **ResNet-50 and VGG-16** perform better compared to AlexNet for facial emotion recognition.



This project provides a comprehensive study of facial emotion recognition using deep learning. By implementing and evaluating multiple CNN models, we demonstrate the effectiveness of deep learning techniques in recognizing human emotions from facial expressions. The project serves as a foundation for future research and real-world emotion-aware applications.

---
