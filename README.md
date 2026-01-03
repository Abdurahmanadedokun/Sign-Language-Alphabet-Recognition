# Sign Language Alphabet Recognition Using Deep Learning

## Project Overview
This project implements a **Convolutional Neural Network (CNN)** to recognize **American Sign Language (ASL) alphabets (A–Y)** from images.  
It demonstrates an end-to-end **image classification pipeline**, including data loading, preprocessing, augmentation, model training, evaluation, and saving the trained model.  

The goal is to build **assistive technology for the hearing-impaired**.

---

## Dataset
- **ASL Alphabet Dataset**: static hand signs (A–Y)
- Excludes motion-based letters (J & Z)
- Images are labeled by letter and stored in folders
- Dataset split into **train** and **validation sets** with augmentation applied

---

## Features
- Data inspection and visualization of hand signs
- Class balance check
- Image augmentation for better generalization
- CNN model with:
  - 3 convolutional layers
  - Max pooling
  - Dropout for regularization
  - Dense layers with softmax output
- Early stopping and model checkpoint to save best model
- Plotting of training/validation accuracy and loss

---

## Folder Structure
