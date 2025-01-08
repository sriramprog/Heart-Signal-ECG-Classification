# Heart-Signal-ECG-Classification

This repository contains a Python script that performs ECG rhythm classification using a 1D Convolutional Neural Network (CNN). The script processes ECG data, trains a deep learning model to classify heartbeats into three categories: normal sinus rhythm, atrial fibrillation, and other rhythms, and evaluates the model's performance using accuracy metrics and visualization.

**Code Overview**
File: ECG_Classification (Updated).py
The single code file encapsulates the entire pipeline from data preprocessing to model training and evaluation. 

Key steps include: <br>
1. Label Encoding: Assigning numeric labels to heartbeat rhythm categories (normal, atrial fibrillation, other rhythms).
2. Data Preprocessing: Extracting ECG features such as amplitudes, peaks, and troughs from a spectrogram.
3. Model Training: Training a 1D CNN model, followed by an attention layer for improved performance.
4. Hyperparameter Tuning: Modifying hyperparameters of the CNN model to optimize accuracy.
5. Visualization: Plotting accuracy graphs for training and validation sets.

How to Use:
1. Clone the Repository:
git clone https://github.com/your-username/ecg-classification.git

2. Install Dependencies:
Ensure that you have all the required libraries:
pip install -r requirements.txt

3. Run the Script: Execute the code using:
python ECG_Classification.py
View the Results: The script will output training and validation accuracy graphs. Adjust hyperparameters as needed to optimize model performance.

References
For a more detailed description of the project, including background, experimental setup, and results, please visit my Notion Repository.
