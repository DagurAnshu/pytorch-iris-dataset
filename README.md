# pytorch-iris-dataset
End-to-end PyTorch Dataset &amp; DataLoader practice using the Iris dataset (Google Colab compatible).
# Iris Dataset – PyTorch Practice Project

This repository contains an end-to-end PyTorch implementation using the Iris dataset.
The main goal of this project is to practice and revise PyTorch fundamentals,
especially custom Dataset and DataLoader creation.

The project is designed to run on Google Colab and focuses on correctness,
clarity, and learning rather than model complexity.

---

## What This Project Covers

- Loading CSV data using Pandas
- Label encoding and feature scaling
- Converting data to PyTorch tensors
- Creating a custom PyTorch Dataset
- Using DataLoader for batching and shuffling
- Building a simple neural network
- Training and evaluation loop
- Optional GPU support in Google Colab

---

## Dataset

- **Name:** Iris Flower Dataset  
- **Source:** Kaggle (public dataset)  
- **Classes:** Setosa, Versicolor, Virginica  
- **Features:** Sepal length, Sepal width, Petal length, Petal width  

---

## Project Structure

pytorch-iris-dataset/
│
├── iris_pytorch_colab.ipynb
└── README.md
├── iris.csv



---

## Results

- Model: Fully connected neural network
- Loss Function: CrossEntropyLoss
- Optimizer: Adam
- Test Accuracy: ~95–100% (may vary due to random initialization)

---

## How to Run (Google Colab)

1. Upload 'Iris.csv' to Google Colab
2. Open 'iris_pytorch_colab.ipynb'
3. Run all cells in order

(Optional)  
Enable GPU:  
Runtime ->Change runtime type -> GPU

---

## Learning Focus

This project focuses on:
- Understanding how PyTorch Dataset and DataLoader work
- Practicing end-to-end machine learning pipelines
- Building confidence with PyTorch training workflows

This project is intended for learning and revision purposes,
not for performance optimization or competition.

---

## Learning Outcomes

- Designed a custom Dataset class in PyTorch
- Gained hands-on experience with DataLoader batching and shuffling
- Practiced model training and evaluation loops
- Improved understanding of tensor shapes and data types

---

## Technologies Used

- Python
- PyTorch
- Pandas
- Scikit-learn
- Google Colab

---

## Author

This project is created as part of a structured learning process
to build strong foundations in PyTorch and in ANNs.



