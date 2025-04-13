# Side Channel Analysis: Implementation of a DPA attack on AES using SCA, neural networks and ASCAD dataset

## Description
This project implements a Differential Power Analysis (DPA) attack on the Advanced Encryption Standard (AES) using side-channel analysis (SCA) techniques. The attack is performed using neural networks and the ASCAD dataset, which contains power traces and corresponding plaintexts and ciphertexts.
The goal is to recover the secret key used in the AES encryption process by analyzing the power consumption patterns during the encryption operation.

## Project Structure
```
SCA/
├── README.md
├── dataset
│   └── ascad.h5
├── models
│   └── ascad_model.h5
└── SCA.ipynb
```

## Requirements
- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- h5py
- scikit-learn

## Results and metrics
- The model achieved an accuracy of <>% on the train set.
- The model achieved an accuracy of <>% on the validation set.
- The model performace was evaluated using guessing entropy, which is a measure of the uncertainty in the key recovery process, 
- The guessing entropy was reduced from 256 bits (for a random key) to <> bits after <> traces, indicating that the model was able to recover the key with high confidence.
- The model was able to recover the key with a guessing entropy of <> bits after <> traces, indicating that the key was fully recovered.