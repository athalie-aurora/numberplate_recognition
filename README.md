# Number Plate Recognition Using CNN

This project implements a system to detect vehicle number plates and recognize the characters on them using Convolutional Neural Networks (CNN).

![Screenshot 2024-06-08 194405](https://github.com/athalie-aurora/numberplate_recognition/assets/119656945/7d374e7b-83e6-4268-9d6b-d4e8f5257d23)

## Overview

This project includes:

- Detection of vehicle number plates using a Haar Cascade classifier.
- Recognition of characters on the number plates using a CNN model.

## Features

- **Detection**: Uses Haar Cascade classifiers to detect number plates in images.
- **Recognition**: Uses a Convolutional Neural Network to recognize and interpret the characters on the number plates.

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/athalie-aurora/numberplate_recognition.git
   cd numberplate_recognition
   ```

2. Environment

 Add virtual environment [download here](https://drive.google.com/drive/folders/1yNgtb8TlkLglAlH8y4ycsIATHwsL5Whv?usp=sharing) by [@athalie-aurora](https://github.com/athalie-aurora)

   ```sh
   auwenv\Scripts\activate
   ```

  or Create and activate a virtual environment 

   ```sh
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

## Image


![Screenshot 2024-06-08 194526](https://github.com/athalie-aurora/numberplate_recognition/assets/119656945/1221b427-8146-4cb9-bbdc-a7088a699dfd)

![Screenshot 2024-06-08 194550](https://github.com/athalie-aurora/numberplate_recognition/assets/119656945/869eaea2-1d5e-4acb-ac98-fb9970259d34)




## Model

The model is built using Keras and TensorFlow. It includes several convolutional layers followed by max-pooling layers, and a dense layer at the end for classification.

## Results

The model achieves high accuracy on the validation set and can recognize characters from number plates with good precision.
