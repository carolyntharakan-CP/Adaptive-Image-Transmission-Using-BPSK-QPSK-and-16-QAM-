# Adaptive-Image-Transmission-Using-BPSK-QPSK-and-16-QAM
#  Project Overview

This project focuses on the design and simulation of an adaptive image transmission system using BPSK, QPSK, and 16-QAM digital modulation techniques in MATLAB. The system transmits grayscale image data through an Additive White Gaussian Noise (AWGN) channel and analyses the effect of channel noise on the received image quality. It also implements an SNR-based adaptive modulation mechanism that automatically selects a suitable modulation technique according to the channel conditions.

# Aim

To design and implement an adaptive digital image transmission system using BPSK, QPSK, and 16-QAM modulation techniques in MATLAB, and evaluate their performance under different noise conditions using Bit Error Rate (BER), Signal-to-Noise Ratio (SNR), and reconstructed image quality.

# Working Principle
1. Image Acquisition: A test image is loaded into MATLAB, converted into grayscale, and resized for processing.

2. Binary Conversion: The image pixel values are converted into a binary bitstream for transmission.

3. Digital Modulation: The binary data is modulated using BPSK, QPSK, or 16-QAM.

4. Noise Addition: An AWGN channel is introduced to simulate real-world communication disturbances.

5. Demodulation: The receiver processes the noisy signal and recovers the transmitted binary data.

6. Image Reconstruction: The recovered bits are converted back into pixel values to reconstruct the received image.

7. Performance Analysis: BER, constellation diagrams, and received image quality are analysed to compare the modulation techniques.

8. Adaptive Modulation: Based on the SNR value, the system automatically selects BPSK, QPSK, or 16-QAM to balance transmission reliability and data rate.

# Technologies Used

- MATLAB: Main programming and simulation environment.

- BPSK: Binary Phase Shift Keying modulation.

- QPSK: Quadrature Phase Shift Keying modulation.

- 16-QAM: 16-Level Quadrature Amplitude Modulation.

- AWGN Channel: Simulates noise during signal transmission.

- Image Processing: Used for image conversion, resizing, and reconstruction.

- BER Analysis: Evaluates transmission accuracy by measuring bit errors.

- SNR-Based Adaptive Selection: Automatically selects the modulation scheme according to channel conditions.

# Outcome

Successfully implemented BPSK, QPSK, and 16-QAM image transmission using MATLAB.
