# PRODIGY_GA_02 – Neural Style Transfer

## 📌 Project Overview
This project implements Neural Style Transfer using Python, PyTorch and a pretrained VGG19 convolutional neural network. It combines the content of one image with the artistic style of another image to generate a new artistic image.

## 🎯 Objective
To understand how deep learning and convolutional neural networks can transfer artistic styles between images.

## 🛠️ Technologies Used
- Python
- PyTorch
- Torchvision
- VGG19
- Google Colab
- Matplotlib
- NumPy
- PIL (Python Imaging Library)

## ⚙️ Methodology
1. Loaded a pretrained VGG19 model.
2. Selected a content image and a style image.
3. Preprocessed both images into tensors.
4. Extracted content and style features using VGG19.
5. Calculated content loss and style loss using Gram matrices.
6. Used an Adam optimizer to generate the stylized image.
7. Displayed and saved the final output.

## 🖼️ Final Output
The project transforms a ballet dancer photograph by applying the artistic patterns and textures of a Cubist-style painting.

The generated result is saved as `Neural_Style_Transfer_Result.png`.

## 📚 Learning Outcomes
- Understanding Neural Style Transfer.
- Learning about pretrained CNN models.
- Understanding VGG19 feature extraction.
- Learning about Gram matrices and loss functions.
- Understanding image optimization using PyTorch.

## 👩‍💻 Internship
Generative AI Internship – Prodigy InfoTech

**Task:** Neural Style Transfer
