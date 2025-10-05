# Music Signal Analysis Using Fourier Transform

This project demonstrates how to analyse and reconstruct a music signal using the **Fourier Transform (FT)** in Python.  
It applies FFT, filtering, and spectrogram visualisation on a short drum audio clip to explore how different frequency bands represent various components of sound.

# Overview

Fourier Transform decomposes a time-domain signal into its frequency components.  
In this project, the signal from `IndustrialDrumLoop.wav` is analysed to:

- Examine frequency content using the **Fast Fourier Transform (FFT)**
- Apply **Low-Pass** and **Band-Pass Filters**
- Visualise spectral energy through **Spectrograms**
- Reconstruct the signal using **Inverse FFT**
- Compute reconstruction error
