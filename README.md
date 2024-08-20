
# Frequency Modulation (FM) with Noise Analysis

## Overview

This repository contains MATLAB and GNU Radio files focused on Frequency Modulation (FM) techniques, including the analysis of noise effects such as Gaussian noise and impulse noise on FM signals. These files serve as a practical resource for understanding how FM works, how noise impacts the signal, and the calculation of performance metrics like Signal-to-Noise Ratio (SNR) and Bit Error Rate (BER).

## Contents

### 1. **MATLAB Codes**

#### **1.1. FM with Gaussian Noise**
   - **Description**: This script demonstrates Frequency Modulation (FM) of an audio signal, followed by the introduction of Gaussian noise. The code includes the generation of the FM signal, addition of noise, and the subsequent calculation of SNR and BER. The script also plots the original audio signal, the integral of the audio signal, the FM signal, and the noisy FM signal.

   - **Key Features**:
     - Audio signal normalization
     - Frequency modulation with a given carrier frequency and modulation index
     - Addition of Gaussian noise to the modulated signal
     - Calculation of SNR and BER
     - Visualization of different stages of the FM process

#### **1.2. FM with Impulse Noise**
   - **Description**: This script is similar to the one above but focuses on the impact of impulse noise on an FM signal. Impulse noise is added at random positions in the FM signal, and the script calculates the SNR and BER. The script also plots the original audio signal, the FM signal, and the FM signal with impulse noise.

   - **Key Features**:
     - Audio signal normalization
     - Frequency modulation with a given carrier frequency and modulation index
     - Addition of impulse noise at random positions in the FM signal
     - Calculation of SNR and BER
     - Visualization of different stages of the FM process

### 2. **GNU Radio Files**

   - **FM with Audio Signal and Noise**
   - **Description**: This folder contains GNU Radio Companion (GRC) files that replicate the MATLAB scripts described above. These GRC files are designed to simulate FM modulation and analyze the impact of both Gaussian and impulse noise on the modulated signal.

   - **Key Features**:
     - Implementation of FM modulation in GNU Radio
     - Addition of Gaussian and impulse noise to the FM signal
     - Analysis and visualization of the modulated and noisy signals

## How to Use

### MATLAB Codes:
1. **Download the MATLAB scripts**: 
   - `FM_Gaussian_Noise.m`
   - `FM_Impulse_Noise.m`

2. **Run the scripts**: 
   - Ensure you have the audio file `counting.wav` in the same directory as the scripts.
   - Run the scripts in MATLAB to generate and analyze the FM signals.

3. **Explore the Results**: 
   - The scripts will display plots of the original audio signal, the modulated signal, and the noisy signal.
   - You can listen to the original and modulated signals and observe the effects of noise on the FM signal.

### GNU Radio Files:
1. **Download the GNU Radio Companion files** from the `GNU_Radio` folder.
2. **Open the GRC files** in GNU Radio Companion.
3. **Run the simulations** to observe FM modulation and the effects of noise.
4. **Explore the output** by analyzing the generated plots and listening to the audio outputs.

## Requirements

- **MATLAB**: Required to run the MATLAB scripts.
- **GNU Radio**: Required to open and run the GNU Radio Companion files.
- **Audio File**: Ensure you have the `counting.wav` file in the same directory as the MATLAB scripts.

## Contributing

If you have any improvements or additional examples related to FM modulation or noise analysis, feel free to contribute by submitting a pull request.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.



