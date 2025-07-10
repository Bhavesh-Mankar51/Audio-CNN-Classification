# Audio CNN Classification

A deep learning project for audio classification using Convolutional Neural Networks (CNNs).

## Technology Used 

Pytorch, Modal, Python, Next.js, Tailwind

## Features

- Audio preprocessing and feature extraction
- CNN-based model architecture for audio classification
- Training, validation, and testing scripts
- Configurable hyperparameters

## Installation

```bash
git clone https://github.com/Bhavesh-Mankar51/Audio-CNN-Classification.git
cd audio-cnn
pip install -r requirements.txt
```

## Usage

1. Open Modal Account

2. Train the model:

    ```bash
    modal run train.py
    ```

3. Model Inference:

    ```bash
    modal deploy main.py
    modal run main.py
    ```

4. Visualize Audio CNN Classfier

    ```bash
    cd audio-cnn-visualization
    npm run dev
    ```    


## Requirements

- Python 3.7+
- PyTorch
- NumPy, librosa, etc.

