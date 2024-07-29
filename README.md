# Automatic-Detection-of-Temporomandibular-Joint-Effusion-with-Deep-Learning-Algorithm

This repository contains the code for the paper "Automatic Detection and Visualization of Temporomandibular Joint Effusion with Deep Neural Network" by Yeon-Hee Lee, Seonggwang Jeon, Jong-Hyun Won, Q-Schick Auh, and Yung-Kyun Noh. The code includes data preprocessing, model training and testing, Grad-CAM heatmap generation, and activation visualization for the detection of TMJ effusion using deep learning techniques.

## Repository Structure

- **Dataset/**
  - `__init__.py`: Initialization file for the dataset module.
  
- **Figures/**
  - `__init__.py`: Initialization file for the figures module.

- **Model_for_effusion/**
  - `__init__.py`: Initialization file for the model module.
  
- **Mymodule/**
  - Contains custom modules and helper functions used throughout the project.

- **1.data_preprocessing.ipynb**
  - Jupyter notebook for data preprocessing. This includes loading the MRI images and clinical data, and preparing them for model training.

- **2.Model_training_Test.ipynb**
  - Jupyter notebook for training and testing the convolutional neural network (CNN) models. It includes three schemes: from-scratch, fine-tuning, and freeze.

- **3.GradCam_Heatmap.ipynb**
  - Jupyter notebook for generating Grad-CAM heatmaps to visualize the regions focused on by the model during prediction.

- **4.Activation_per_layer.ipynb**
  - Jupyter notebook for visualizing activations per layer in the CNN model to understand how the model processes the input data.

- **LICENSE**
  - License file for the project.

- **README.md**
  - This file. Provides an overview of the project and instructions for use.

## Installation and Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SeonggwangJeon/Automatic-Detection-of-Temporomandibular-Joint-Effusion-with-Deep-Learning-Algorithm.git
   cd Automatic-Detection-of-Temporomandibular-Joint-Effusion-with-Deep-Learning-Algorithm

## Contact
 **For any questions or issues, please contact:**
  - Yeon-Hee Lee: omod0209@gmail.com
  - Yung-Kyun Noh: nohyung@hanyang.ac.kr
  - Seonggwang Jeon: qq22512@hanyang.ac.kr

## Acknowledgments
  - This work was supported by the Department of Orofacial Pain and Oral Medicine, Kyung Hee University Dental Hospital, and the Department of Computer Science, Hanyang University.**
