# Deep-Learning-Assignment2

CNN | RNN Variants | Generative Adversarial Networks
Course: Deep Learning (IS3332-1)
Student: Manish
USN: NNM23IS092
Section & Semester: 6th B
Institution: NMAM Institute of Technology, Nitte
Submitted To: Dr. Jason Elroy Martis, Associate Professor
Date: 23-03-2026

📌 Overview
This repository contains the implementation of three deep learning models as part of Assignment 2:
TaskModelDatasetImage ClassificationCustom CNN + ResNet18 (Transfer Learning)Fashion-MNISTSentiment ClassificationRNN, LSTM, GRUIMDB Movie ReviewsImage GenerationGenerative Adversarial Network (GAN)Fashion-MNIST

📂 Repository Structure
Deep-Learning-Assignment2/
│
├── Manish_NNM23IS092_DL_task2.ipynb   # Main Colab Notebook (all 3 tasks)
└── README.md                           # Project documentation

🚀 How to Run

Click the Open in Colab button below
Go to Runtime → Run All
All models will train and display results automatically

Show Image

🧠 Models Implemented
Task A — Convolutional Neural Network (CNN)

Custom CNN with 2 convolutional blocks, Batch Normalisation, Dropout
Transfer Learning using pretrained ResNet18
Dataset: Fashion-MNIST (70,000 images, 10 classes)

ModelTest AccuracyCustom CNN92.05%ResNet18 (Transfer Learning)67.29%

Task B — Recurrent Neural Networks

Simple RNN, LSTM, and GRU for binary sentiment classification
Dataset: IMDB Movie Reviews (50,000 reviews)

ModelTest AccuracySimple RNN81.12%LSTM85.21%GRU86.81%

Task C — Generative Adversarial Network (GAN)

Generator: 3 Dense layers → produces 28×28 clothing images
Discriminator: 2 Dense layers → classifies real vs fake
Dataset: Fashion-MNIST
Trained for 30 epochs — discriminator accuracy stabilised at ~50%


🛠️ Technologies Used

Python 3.x
PyTorch (CNN, ResNet18)
TensorFlow / Keras (RNN, LSTM, GRU, GAN)
Torchvision
Matplotlib, Seaborn
Google Colab (GPU)


📊 Key Results

Custom CNN outperformed ResNet18 on Fashion-MNIST due to domain mismatch with ImageNet
GRU achieved the best accuracy (86.81%) among all recurrent models
GAN successfully generated recognisable clothing images after adversarial training


📁 Dataset Sources

Fashion-MNIST
IMDB Dataset


📚 References

Goodfellow et al., Deep Learning, MIT Press, 2016
PyTorch Documentation — https://pytorch.org/docs/
TensorFlow Documentation — https://www.tensorflow.org/


📝 Academic Integrity
This assignment is my own original work submitted as part of the Deep Learning course (IS3332-1) at NMAM Institute of Technology, Nitte.ShareContentpdfpdf
