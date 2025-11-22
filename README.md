This project implements an end-to-end image classification system using modern deep learning models.
It provides:

Dataset loading & preprocessing

Training, validation, and testing

Model evaluation

Prediction on custom images

Support for multiple architectures

The purpose of the project is to provide a flexible, modular template for experimenting with different convolutional neural network (CNN) models.

🧠 Supported Deep Learning Models

You can train the classifier using any of the following:

✔️ ResNet Family

ResNet18

ResNet34

ResNet50

✔️ VGG Family

VGG16

VGG19

✔️ EfficientNet

EfficientNet-B0

EfficientNet-B1

✔️ MobileNetV2

Lightweight and perfect for mobile/edge devices.

✔️ DenseNet

DenseNet121

✔️ Custom CNN Model

Your own architecture is also supported.

Just update the model selector in the code.

📁 Project Structure
├── data/
│   ├── train/
│   ├── test/
│   └── val/
├── models/
│   ├── resnet.py
│   ├── vgg.py
│   ├── efficientnet.py
│   └── mobilenet.py
├── utils/
│   ├── dataset_loader.py
│   ├── train.py
│   ├── evaluate.py
│   └── predict.py
├── main.py
├── requirements.txt
└── README.md
