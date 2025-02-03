# Deep Audio Classifier

A deep learning model designed to classify audio signals, leveraging Convolutional Neural Networks (CNNs) for accurate audio recognition.

## Project Overview

This project focuses on developing a deep audio classifier capable of distinguishing between audio clips of capuchin birds and other sounds. The model processes audio data by converting waveforms into spectrograms, which are then fed into a CNN for classification.

## Features

- **Audio Preprocessing**: Downsamples audio to 16 kHz, trims or pads waveforms to 3 seconds, and converts them into spectrograms for feature extraction.
- **Model Architecture**: Utilizes a CNN with ReLU activation functions in hidden layers and a Sigmoid activation function in the output layer for binary classification.
- **Data Pipeline Optimization**: Incorporates caching, shuffling, batching, and prefetching to efficiently handle large audio datasets.

## Project Structure


## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/klokeshgupta/Deep-audio-classifier.git
   cd Deep-Audio-Classifier

## Usage

**Prepare Your Dataset:**

- Place your audio files in the `data/` directory, organized into subdirectories for each class.


**Contributing **
Contributions are welcome! Please feel free to submit a pull request or open an issue for any improvements or bugs.
