# MLP-Based Intrusion Detection System for Network Traffic

## Overview
This project uses a Multi-Layer Perceptron (MLP) to classify network traffic as normal or as attacks (ICMP, SYN, UDP) to enhance security. 🔍

## Objective
To develop a machine learning model that automatically classifies incoming network packets and identifies security threats. ⚠️

## Dataset
- **Description**: Captured network traffic with four classes: Normal, ICMP, SYN, and UDP.
- **Data Collection**: Data was collected using **Wireshark**. In a virtual machine environment, various network attacks were simulated to capture packets, which were then used for training and testing the model. 💻

## Methodology
1. **Data Preprocessing**: Cleaning and normalization of the dataset. 🧹
2. **Model Architecture**: MLP designed with input, hidden, and output layers. 🏗️
3. **Training**: Model trained on the dataset with relevant metrics. 📈
4. **Evaluation**: Performance assessed with a test set and confusion matrix. 📊

## Results
- Achieved an accuracy of **76.24%** on the test dataset. 🎉
