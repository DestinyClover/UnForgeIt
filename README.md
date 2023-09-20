
# UnForgeIt
Traditional methods for signature verification often rely on manual inspection, which is time-consuming, subjective, and prone to human errors. In recent years, the advent of machine learning techniques has shown promise in automating signature forgery detection, offering a more efficient and objective approach. The Project will help to identify whether a given signature is real or forged. 

#### -- Project Status: Active

## Introduction
Signature forgery is a significant problem in various domains including banking, legal documentation, and forensic investigations. Traditional methods for signature verification often rely on manual inspection, which is time-consuming, subjective, and prone to human errors. This paper presents a comprehensive review and comparative analysis of signature forgery detection methods using machine learning. The proposed method involves the extraction of prominent features like stroke patterns, curvature, angles, and other relevant characteristics that differentiate genuine signatures from forged ones and using them as input to train the model. The model is then used to classify whether a new signature is genuine or forged. This methodology can be applied in real-world scenarios, such as detecting fraudulent checks and documents. 

### Methods Used
* Machine Learning
* Data Visualization
* Predictive Modeling
* etc.

### Languages and libraries used
* Python
* Tensorflow
* Matplotlib
* Pandas
* Keras
  
## Methodology
* Data Collection: Dataset of genuine and forged signatures was collected ensuring different writing styles and strokes. To train the robust model a significant number of dataset was collected
* Data preprocessing: In this process, several techniques are applied to prepare the signature data. These include image normalization, resizing, and cropping to ensure consistent image dimensions. 
* Feature Extraction: Feature extraction is a critical step in signature forgery detection, where relevant information is extracted from the preprocessed signature data to capture discriminative patterns and characteristics. Learned features can be obtained using deep learning architectures, such as Convolutional Neural Networks (CNNs), which automatically learn discriminative features from raw signature images.
* Feature Selection: It aims to reduce dimensionality, improve model efficiency, and enhance detection accuracy. Various techniques can be used for feature selection, including filter methods, wrapper methods, and embedded methods.
* Training and Testing Split: Training and testing split in signature forgery detection involves dividing the available dataset into two subsets: one for training the model and another for evaluating its performance. 
* Model Training: The training process typically involves forward propagation, where the input data is passed through the model, and backward propagation, where gradients are computed to update the model's parameters. The goal of model training is to achieve high accuracy and robustness in detecting signature forgeries. 
  
## Needs of this project

- Banking and Financial Institutions
- Legal and Forensic Investigations
- Document Verification and Authentication
- Fraud Detection and Prevention
- Compliance and Regulatory Requirements
- Digital Document Authentication
- Law Enforcement and Forensic Analysis
- Counterfeit Detection in Art and Collectibles


