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
Question 1: Cloud Computing for Deep Learning
(a) Elasticity and Scalability in Cloud Computing for Deep Learning:
•	Elasticity: In the context of cloud computing for deep learning, elasticity refers to the ability to automatically scale resources up or down based on demand. This ensures that computational power, storage, and other resources can be adjusted dynamically as workloads change, helping to optimize cost and performance. For deep learning tasks, this means you can use more computing resources when training large models and reduce the number of resources during idle times, offering cost savings and efficiency.
•	Scalability: Scalability refers to the capacity of a cloud platform to handle increasing workloads or the ability to scale its resources (compute, storage, etc.) in a way that allows a system to handle growing demands without performance degradation. For deep learning, scalability is critical because training deep models often requires large datasets and high computational power. A scalable system can efficiently expand resources to support larger models, more data, or higher throughput.
(b) Comparison of AWS SageMaker, Google Vertex AI, and Microsoft Azure Machine Learning Studio:
1.	AWS SageMaker:
o	Deep Learning Capabilities: AWS SageMaker offers a fully managed environment for building, training, and deploying machine learning models, including deep learning models. It supports popular frameworks like TensorFlow, PyTorch, and MXNet. SageMaker provides various tools like built-in algorithms, pre-configured instances with GPU support, and automatic model tuning. It also integrates well with other AWS services, such as S3 for storage and EC2 for computing.
o	Strengths: Strong integration with AWS ecosystem, extensive model deployment options, automated machine learning (AutoML), and model optimization capabilities. It also supports distributed training and model monitoring.
2.	Google Vertex AI:
o	Deep Learning Capabilities: Vertex AI by Google Cloud is a managed machine learning platform that simplifies the process of developing and deploying models at scale. It supports TensorFlow, PyTorch, and other frameworks, and offers AutoML for training custom models. Vertex AI integrates well with Google Cloud services like BigQuery and Cloud Storage, and it provides tools for hyperparameter tuning and model monitoring.
o	Strengths: Excellent for integration with Google Cloud's data processing and big data tools, auto-scaling for training workloads, and strong support for AI model deployment. It also features Vertex AI Workbench, a unified development environment.
3.	Microsoft Azure Machine Learning Studio:
o	Deep Learning Capabilities: Azure Machine Learning Studio is a cloud-based service for building, training, and deploying machine learning models, including deep learning. It supports TensorFlow, PyTorch, and other common deep learning frameworks. Azure ML provides various compute options, including virtual machines with GPU support, and integrates well with Azure's extensive data services.
o	Strengths: Provides a collaborative environment for model building, strong integration with the Azure ecosystem, and robust support for MLOps, model deployment, and versioning. Azure ML also supports automated machine learning and scalable distributed training.



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
