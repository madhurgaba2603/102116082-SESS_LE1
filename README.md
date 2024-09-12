# Speech Command Recognition

This assignment demonstrates a simple speech command recognition model using TensorFlow and the Speech Commands dataset. The model is trained to recognize different spoken words from a set of pre-defined commands.

## Overview

The goal of this project is to classify short audio snippets (1 second or less) into one of several predefined speech commands. The dataset used is the [Speech Commands Dataset](http://download.tensorflow.org/data/speech_commands_v0.02.tar.gz), which contains utterances of 35 words by thousands of different speakers.

## Features

- Loads and preprocesses the Speech Commands dataset.
- Converts raw audio waveforms to spectrograms for use in the model.
- Trains a CNN model to classify the audio commands.
- Predicts the command from a new audio file.
- Visualizes the waveform and spectrogram of the audio.
- Includes a real-time prediction functionality for custom audio files.

## Assignment Tasks

1. **Paper Summary**:  
   Read and summarize the paper in about 50 words.

2. **Dataset Analysis**:  
   Download the dataset mentioned in the paper. Statistically analyze and describe the dataset, so that it may be useful for future reference.  
   - Include code snippets in a `.ipynb` file to evidence your analysis.

3. **Classifier Training**:  
   Train a classifier so that you are able to distinguish the commands in the dataset.

4. **Performance Reporting**:  
   Report the performance results using standard benchmarks.

5. **Custom Command Dataset**:  
   Record about 30 samples of each command in your voice and create a new dataset (including a new user ID for yourself).  
   - You may use a timer on your computer to synchronize.

6. **Model Fine-Tuning**:  
   Fine-tune your classifier to perform on your voice.

7. **Final Results**:  
   Report the results of the fine-tuned model.

## Requirements

- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook


