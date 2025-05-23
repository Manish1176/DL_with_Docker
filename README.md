# 🧠 Deep Learning with Docker – Fashion MNIST 👕

This project demonstrates how to build, train, and evaluate a deep learning model on the Fashion MNIST dataset using **TensorFlow/Keras**, and how to **containerize** the entire workflow using **Docker** for easy deployment and reproducibility.

---

## 📂 Project Structure

├── Dockerfile
├── requirements.txt
├── fashion_mnist_training.py
├── model/ # Saved model (optional)
└── README.md


---

## 🛠️ Tech Stack

- Python  
- TensorFlow / Keras  
- Docker  
- Fashion MNIST dataset  

---

## 📌 Features

- Loads and preprocesses the Fashion MNIST dataset  
- Builds a Convolutional Neural Network (CNN) model  
- Trains and evaluates the model on test data  
- Dockerized setup for environment consistency and portability  

---

## docker build -t fashion-mnist-dl .

## docker run fashion-mnist-dl

## 📊 Dataset
Fashion MNIST by Zalando Research

60,000 training and 10,000 test grayscale images (28x28) across 10 clothing categories

## 📝 Output
Model accuracy and loss metrics

Trained model saved (optional)

Console-based result summary


