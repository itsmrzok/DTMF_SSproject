# DTMF Decoder Using MATLAB

This project implements a **Dual-Tone Multi-Frequency (DTMF) Decoder** using MATLAB to simulate telecommunication signal decoding. The decoder identifies key presses on a virtual keypad based on unique frequency tones, providing a practical example of signal processing in telecommunications.

## Project Details

- **Project Title:** DTMF Decoder Using MATLAB
- **Subject:** Signals and Systems
- **Submitted to:** Mr. Umair Khorie
- **Authors:** Zameer Abbas (Roll No: 22CS078), ali (Roll No: 22CS032)

## Overview

This project creates a MATLAB GUI that decodes DTMF signals by processing them with Chebyshev filters and the Fast Fourier Transform (FFT). The GUI accepts input from a virtual keypad, processes the signals, and displays the corresponding key based on the input tones.

### Objectives

1. Design a MATLAB GUI to simulate and decode DTMF signals.
2. Apply signal filtering techniques to isolate frequency components.
3. Decode and display the corresponding key based on input signals.

### Key Components

- **DTMF Signal Generation**: Each keypad button corresponds to a combination of low and high frequencies.
- **Chebyshev Filters**: Used to filter out low and high frequency ranges in the signals.
- **FFT Analysis**: Converts signals into the frequency domain for easier analysis and decoding.

### Tools and Techniques

- **MATLAB**: For GUI and signal processing.
- **Chebyshev Filters**: To isolate specific frequencies in DTMF signals.
- **FFT**: For frequency analysis to match with DTMF frequency pairs.

## Running the Project

### Prerequisites

1. **MATLAB**: Ensure MATLAB is installed with the Signal Processing Toolbox.
2. **Project Files**: Download all project files, including `subdecode.m` and `decode.m`, to run the decoder.

### How to Run the Program

1. **Open MATLAB** and navigate to the directory containing the project files.
2. In the MATLAB Command Window, **run the main file `decode.m`** by typing:
   ```matlab
   run('decode.m')
