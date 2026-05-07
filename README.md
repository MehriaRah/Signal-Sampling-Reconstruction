# Signal-Sampling-Reconstruction
MATLAB-based analysis of the Nyquist-Shannon Sampling Theorem, demonstrating signal reconstruction through Whittaker-Shannon interpolation and the visual/mathematical impact of aliasing.


 ## 🚀 Overview
This project provides a robust simulation of Signal Sampling and Reconstruction using MATLAB. It serves as a technical demonstration of how continuous-time signals are digitized and accurately recovered using **Sinc Interpolation**, while highlighting the boundary conditions where information loss (aliasing) occurs.

## 🛠️ Key Technical Features

**Signal Synthesis:** Generated a multi-component sinusoidal signal with a maximum frequency of 8 Hz.
Whittaker-Shannon Interpolation: Implemented a reconstruction algorithm from scratch using the `sinc` function to recover the original signal from discrete data points.

**Nyquist Analysis:** Mathematically determined the critical sampling threshold (n < 25) to prevent signal distortion.*
**Dynamic Visualizations:** Developed dual-subplot figures to compare:
    1.  Time-domain sampling vs. continuous signal.
    2.  Original signal vs. reconstructed approximation to validate fidelity.

## 📊 Results Summary

**Theorem Satisfied (n=10):** With a sampling frequency of $40 \text{ Hz}$ (well above the $16 \text{ Hz}$ Nyquist rate), the reconstruction achieves near-perfect fidelity.
**Aliasing Demonstrated (n=30):** Sampling at $13.3 \text{ Hz}$ violates the theorem, causing high-frequency components to be "aliased" into lower frequencies, demonstrating a clear loss of signal integrity.

## 💻 Skills Demonstrated

 **Digital Signal Processing (DSP)**
 **MATLAB Programming**
 **Mathematical Modeling & Simulation**
 **Data Visualization**


<img width="1600" height="900" alt="WhatsApp Image 2026-05-07 at 21 08 50" src="https://github.com/user-attachments/assets/78e44fca-9147-470a-9d82-b4f8a5e8686d" />

<img width="1600" height="900" alt="WhatsApp Image 2026-05-07 at 21 09 28" src="https://github.com/user-attachments/assets/901e7c33-6ec5-424c-bfbd-6fcbdfd972ab" />

