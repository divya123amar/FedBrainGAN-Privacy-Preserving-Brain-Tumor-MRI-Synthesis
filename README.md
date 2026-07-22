# Brain Tumor Classification Using VGG16 Transfer Learning

A deep learning framework for automated brain tumor classification from MRI images using the pre-trained VGG16 convolutional neural network and transfer learning. This project demonstrates image preprocessing, model training, validation, and performance evaluation using TensorFlow and Keras.

---

## 📌 Overview

Brain tumor diagnosis from magnetic resonance imaging (MRI) is a challenging task that requires accurate image interpretation. This project utilizes Transfer Learning with the VGG16 architecture to classify brain MRI images efficiently while reducing computational complexity and training time.

The model leverages pre-trained ImageNet weights and fine-tunes the network for brain tumor classification.

---

## 🚀 Features

- Transfer Learning using VGG16
- MRI image preprocessing
- Data augmentation
- Model training and validation
- Performance evaluation
- Accuracy and loss visualization
- TensorFlow & Keras implementation

---

## 📂 Project Structure

```
Brain-Tumor-VGG16/
│
├── Transfer Learning VGG16.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
└── dataset/
```

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

---

## 📊 Workflow

1. Load MRI image dataset
2. Preprocess images
3. Perform data augmentation
4. Load pre-trained VGG16 model
5. Freeze base layers
6. Add custom classification layers
7. Train the model
8. Evaluate model performance
9. Visualize training results

---

## 📈 Model Architecture

- Pre-trained VGG16
- Global Average Pooling
- Dense Layer
- Dropout
- Softmax Output Layer

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Brain-Tumor-VGG16.git
```

Move into the project directory

```bash
cd Brain-Tumor-VGG16
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run

Open the notebook

```bash
jupyter notebook
```

or

```bash
python train.py
```

(if converted into Python scripts)

---

## 📊 Results

The notebook includes:

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Performance Evaluation

---

## 📁 Dataset

This project uses the **Brain Tumor Segmentation (BraTS) 2020** dataset, a publicly available benchmark for brain tumor analysis and segmentation. The dataset contains multi-modal MRI scans with expert-annotated tumor labels.

### Dataset Information

- **Dataset:** BraTS 2020
- **Modalities:** T1, T1Gd (T1ce), T2, and FLAIR
- **Image Format:** NIfTI (.nii.gz)
- **Ground Truth:** Expert-annotated segmentation masks
- **Classes:** Background, Necrotic Tumor Core, Peritumoral Edema, Enhancing Tumor

### Download

The dataset can be obtained after registration from the official BraTS challenge website:

**Official Website:** https://www.med.upenn.edu/cbica/brats2020/

Alternatively, the preprocessed dataset is available on Kaggle:

https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation

### Dataset Structure

```
BraTS2020/
│
├── BraTS20_Training_001/
│   ├── BraTS20_Training_001_flair.nii.gz
│   ├── BraTS20_Training_001_t1.nii.gz
│   ├── BraTS20_Training_001_t1ce.nii.gz
│   ├── BraTS20_Training_001_t2.nii.gz
│   └── BraTS20_Training_001_seg.nii.gz
│
├── BraTS20_Training_002/
│
└── ...
```

Place the downloaded dataset inside the project directory and update the dataset path in the notebook before training.

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome. Feel free to fork this repository and submit pull requests.

---

## 👩‍💻 Author

**Divyashree A**

Research Scholar

Department of Computer Science and Engineering

---

⭐ If you find this project useful, please consider giving it a star.
