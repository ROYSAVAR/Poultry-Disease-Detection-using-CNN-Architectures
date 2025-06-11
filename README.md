# 🐔 Poultry Disease Detection using CNN Architectures

This repository contains a comparative study of three Convolutional Neural Network (CNN) architectures — ResNet-18, ResNet-34, and ResNet-50 — applied to the task of poultry disease detection using image data. The objective is to evaluate the performance of these models in terms of classification accuracy, computational efficiency, and suitability for real-world deployment in veterinary and agricultural contexts.

## 📁 Project Structure

- `resnet18.py`: Training and evaluation scripts for ResNet-18
- `resnet34.py`: Training and evaluation scripts for ResNet-34
- `resnet50.py`: Training and evaluation scripts for ResNet-50
- `Poultry-Disease-Detection-using-CNN-Architectures.pdf`: Full report of the project

## 📦 Dataset

To run the experiments, download the **Poultry Diseases dataset** from Kaggle:

🔗 https://www.kaggle.com/datasets/chandrashekarnatesh/poultry-diseases

Once downloaded, extract the dataset and update the file paths in the scripts according to your local setup.

## 🚀 Getting Started

No special configuration is needed beyond setting the correct dataset path.

Example:
```python

dataset = datasets.ImageFolder(root='C:/Users/your_user/data_folder/train', transform=data_transforms)

```

## 📑 Report
The file Poultry-Disease-Detection-using-CNN-Architectures.pdf contains the complete project report, including methodology, experiments, and conclusions.

🧠 CNN Architectures
Each architecture folder (resnet18, resnet34, resnet50) contains:

Model definition and training scripts

Evaluation and metric calculations

Optional visualizations and performance logs

##💡 Notes
The dataset is not included in this repository due to size constraints. You may find a compressed version (e.g., data.zip) instead.

Be sure to update all dataset paths before running the scripts.

GPU (CUDA) support is recommended for faster training but not required.

##📜 License
This project is intended for academic and educational use only. Please refer to the Kaggle dataset license for usage rights.


