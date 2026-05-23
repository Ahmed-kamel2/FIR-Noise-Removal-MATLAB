# FIR Filter Noise Removal System using MATLAB & Digital Signal Processing

## Overview

This project presents the design and implementation of a Moving-Average Finite Impulse Response (FIR) Filter for removing high-frequency noise from a desired low-frequency signal using MATLAB. The project focuses on Digital Signal Processing (DSP) concepts including signal generation, FIR filtering, FFT spectrum analysis, visualization, and hardware implementation concepts.

The system demonstrates how a 50 Hz useful signal corrupted by 10 kHz noise can be filtered effectively using a tapped-delay-line FIR filter structure.

---

## Objectives

* Generate noisy discrete-time signals
* Implement a Moving-Average FIR Filter
* Remove high-frequency noise from signals
* Analyze signals in both time and frequency domains
* Perform FFT spectrum analysis
* Visualize filtering performance using MATLAB plots
* Understand FIR hardware implementation concepts

---

## Technologies Used

* MATLAB
* Digital Signal Processing (DSP)
* FFT Analysis
* FIR Filter Design
* Signal Visualization

---

## Project Workflow

### 1. Signal Generation

* Generate a 50 Hz desired signal
* Generate a 10 kHz noise signal
* Combine both signals with DC offset

### 2. FIR Filter Design

* Implement a Moving-Average FIR Filter
* Use tapped-delay-line architecture
* Apply filtering sample-by-sample

### 3. Signal Visualization

* Plot noisy and filtered signals
* Compare time-domain waveforms

### 4. FFT Spectrum Analysis

* Apply Fast Fourier Transform (FFT)
* Analyze frequency-domain behavior
* Compare noise before and after filtering

### 5. Hardware Implementation

* Explain FIR filter hardware architecture
* Demonstrate delay registers and adder networks
* Discuss FPGA-based implementation concepts

---

## Key Features

* MATLAB-based FIR Filter implementation
* Noise removal using Moving-Average filtering
* Time-domain and frequency-domain analysis
* FFT spectrum visualization
* Hardware implementation overview
* DSP concepts for mechatronics applications

---

## Results

The FIR filter successfully reduced the 10 kHz high-frequency noise while preserving the desired 50 Hz signal. The project demonstrates the effectiveness of FIR filtering techniques in Digital Signal Processing applications.

---

## Repository Structure

```bash
├── MATLAB_Code/
├── Project_Report/
├── Hardware_Implementation/
├── Images/
├── README.md
└── FIR_Filter.m
```

---

## Future Improvements

* Implement advanced FIR filter designs
* Compare FIR and IIR filters
* Deploy the filter on FPGA hardware
* Add real-time signal processing
* Optimize filter performance

---

## Author

Ahmed Mohamed Kamel

Mechatronics Engineering Student
Arab Academy for Science & Technology (AAST)

GitHub:
https://github.com/Ahmed-kamel2

LinkedIn:
https://www.linkedin.com/in/ahmed-mohamed-kamel1
