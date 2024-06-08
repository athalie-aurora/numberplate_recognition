# Number Plate Recognition Using CNN

This project implements a system to detect vehicle number plates and recognize the characters on them using Convolutional Neural Networks (CNN). The project is focused on recognizing number plates from Punjab, but can be adapted for other regions.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

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

2. Create and activate a virtual environment:

   ```sh
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Place the images you want to process in the `images` directory.
2. Run the script to detect and recognize number plates:
   ```sh
   python main.py
   ```

## Model

The model is built using Keras and TensorFlow. It includes several convolutional layers followed by max-pooling layers, and a dense layer at the end for classification.

## Results

The model achieves high accuracy on the validation set and can recognize characters from number plates with good precision.
