# CS5720 Neural Networks and Deep Learning - Home Assignment 2

## Student Information
**Name:** Pavani Seelam
**University:** University of Central Missouri  
**Course:** CS5720 - Neural Networks and Deep Learning  
**Semester:** Spring 2025  

---

## Assignment Overview
This repository contains solutions for **Home Assignment 2**, covering Chapters 4 and 5 of the course. The assignment consists of theoretical and coding tasks related to cloud computing, convolution operations, CNN feature extraction, and deep learning architectures.

---

## Table of Contents
1. [Question 1: Cloud Computing for Deep Learning](#question-1-cloud-computing-for-deep-learning)
2. [Question 2: Convolution Operations](#question-2-convolution-operations)
3. [Question 3: CNN Feature Extraction](#question-3-cnn-feature-extraction)
4. [Question 4: Implementing CNN Architectures](#question-4-implementing-cnn-architectures)
5. [How to Run the Code](#how-to-run-the-code)
6. [Results and Outputs](#results-and-outputs)

---

## Question 1: Cloud Computing for Deep Learning
- Defined **elasticity** and **scalability** in cloud computing.
- Compared **AWS SageMaker**, **Google Vertex AI**, and **Azure ML Studio** for deep learning capabilities.

📄 **File:** `cloud_computing.md`  

---

## Question 2: Convolution Operations
Implemented convolution operations with different **stride and padding** using **NumPy** and **TensorFlow/Keras** on a 5×5 input matrix with a 3×3 kernel.

📄 **File:** `convolution.py`  

### Implemented Cases:
✅ Stride = 1, Padding = ‘VALID’  
✅ Stride = 1, Padding = ‘SAME’  
✅ Stride = 2, Padding = ‘VALID’  
✅ Stride = 2, Padding = ‘SAME’  

---

## Question 3: CNN Feature Extraction
**Task 1:** Edge detection using Sobel filters in OpenCV.  
**Task 2:** Max Pooling and Average Pooling using TensorFlow/Keras.  

📄 **Files:**  
- `edge_detection.py`
- `pooling_operations.py`

### Outputs:
✅ Original image and edge-detected images (Sobel-X & Sobel-Y).  
✅ Original, max-pooled, and average-pooled matrices.

---

## Question 4: Implementing CNN Architectures
Implemented **AlexNet** and **ResNet-like** models using **TensorFlow/Keras**.

📄 **Files:**  
- `alexnet.py` (AlexNet implementation)  
- `resnet.py` (Residual block & ResNet implementation)  

### Outputs:
✅ Model summary for AlexNet.  
✅ Model summary for the ResNet-like model.

---

## How to Run the Code
1. Clone the repository:  
   ```bash
   git clone https://github.com/[YourGitHubUsername]/[RepositoryName].git
   cd [RepositoryName]
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Python scripts:

bash
Copy
Edit
python convolution.py
python edge_detection.py
python pooling_operations.py
python alexnet.py
python resnet.py
