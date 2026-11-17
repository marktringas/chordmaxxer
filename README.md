# chordmaxxer

This repository was made to train a neural network to recognize the 8 open chord on guitar. The current model found in src has a 99% accuracy. If you wish to retrain the model yourself you can follow these steps:

1. Generate Images - Run the code from top to bottom in wav-to-spectrogram.ipynb. This should take no longer than 5 minutes and will generate roughly 4000 images for the model to train on.

2. Train Model - Run the code from top to bottom in model.ipynb. The training process should take no longer than 35 minutes.