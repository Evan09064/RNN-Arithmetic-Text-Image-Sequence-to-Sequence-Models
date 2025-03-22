# Arithmetic RNN Models – Sequence-to-Sequence Learning (Project A2 Group36)

## Overview
This repository contains our experiments with encoder-decoder RNN models for performing arithmetic operations (addition, subtraction, multiplication) on both text and image modalities. The project covers three types of models:
- **Text-to-text:** Input and output as encoded strings.
- **Image-to-text:** Input as a sequence of MNIST images, output as text.
- **Text-to-image:** Input as text and output as a sequence of images.

These experiments not only demonstrate proficiency in RNN architectures (including LSTM layers, RepeatVector, TimeDistributed layers, etc.) but also build a foundation for sequence-to-sequence learning—an approach applicable in interactive narrative systems and dynamic content generation in gaming.

## Setup & Requirements
- **Python 3.8+**
- **Libraries:** TensorFlow, Keras, NumPy, matplotlib, OpenCV, etc.
- To install dependencies, run:
  ```bash
  pip install -r requirements.txt

