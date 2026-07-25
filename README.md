# 👁️ Iris Verification System

An experimental biometric verification project exploring classical image processing,
feature representation, similarity matching, and deep learning approaches for iris recognition.

## 🧬 About the Project

This project investigates how iris patterns can be used for biometric verification.

The goal is to build an end-to-end system that compares two iris images and determines
whether they belong to the same biometric identity.

Rather than focusing only on classification accuracy, the project will explore the
complete biometric pipeline — from image preprocessing and iris segmentation to
feature extraction, similarity matching, and biometric performance evaluation.

The project also aims to compare classical image-processing approaches with
deep feature representations.

## 🔬 Research Questions

This project will explore questions such as:

- How effectively can iris texture be represented using handcrafted features?
- How do different similarity metrics affect verification performance?
- How do classical feature representations compare with deep embeddings?
- How sensitive is iris verification to image degradation such as blur, noise,
  illumination changes, and rotation?

## ⚙️ Planned Pipeline

Iris Image  
↓  
Iris & Pupil Segmentation  
↓  
Iris Normalization  
↓  
Image Enhancement  
↓  
Feature Extraction  
↓  
Similarity Matching  
↓  
Verification Decision  
↓  
Biometric Performance Evaluation

## 🧠 Methods

The project is planned to explore:

### Image Processing
- Grayscale processing
- Contrast enhancement
- Noise reduction
- Iris and pupil segmentation
- Polar iris normalization

### Classical Feature Representation
- Local Binary Patterns (LBP)
- Histogram of Oriented Gradients (HOG)

### Matching
- Euclidean distance
- Cosine similarity

### Deep Learning
Later experiments will investigate CNN-based feature embeddings and compare
their verification performance with handcrafted representations.

## 📊 Evaluation

Performance will be evaluated using biometric verification metrics including:

- False Acceptance Rate (FAR)
- False Rejection Rate (FRR)
- Equal Error Rate (EER)
- Receiver Operating Characteristic (ROC)
- Area Under the Curve (AUC)

Genuine and impostor score distributions will also be analyzed to understand
the separation between matching and non-matching iris pairs.

## 🧪 Robustness Experiments

Later stages of the project will investigate how verification performance changes under:

- Gaussian blur
- Image noise
- Brightness changes
- Contrast changes
- Rotation

## 📂 Project Structure

iris-verification/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── 01_dataset_exploration.ipynb
│
├── src/
├── results/
│
├── README.md
├── requirements.txt
└── .gitignore

## 🛠️ Technologies

- Python
- NumPy
- Pandas
- OpenCV
- Matplotlib
- scikit-image
- scikit-learn
- Jupyter

## 📍 Current Status

🚧 **Work in progress**

Current milestone:

**Dataset exploration and preparation**

The next stages will focus on iris segmentation and normalization.

## 🎯 Long-Term Goal

The long-term goal is to compare classical and deep-learning approaches to
iris verification and investigate their robustness under different image conditions.

Future extensions may include multimodal biometric verification by combining
iris and facial biometric information.

---

Built as an independent exploration of biometrics, computer vision,
machine learning, and the mathematics behind biometric verification.