# FPGA-Based-Real-Time-Spoken-Digit-Recognition
Senior design project involving design and implementation of a complete electrical and electronics engineering system. Development involving multiple areas of electrical and electronics engineering. Simulations. Prototype development and testing. 

Developed and implemented a complete spoken number recognition system on a Basys-3 FPGA platform. The project included designing a microphone amplifier with anti-aliasing filters, digitizing audio signals via an ADC module, and processing data using FPGA. Employed Mel-Frequency Cepstral Coefficients (MFCC), FFT, windowing techniques, and discrete cosine transform (DCT) to extract speech features. Final digit recognition was performed using Euclidean distance metrics. The system achieved high accuracy verified through MATLAB simulations.

Skills involved: FPGA Design (VHDL), MATLAB, PCB Design (Altium Designer), Signal Processing, Analog Circuit Simulation (LTspice), UART Communication.

This repository presents a senior design project that implements a spoken digit recognition pipeline on a Basys-3 FPGA. It covers:

Lab-DEBUG: UART-based data transfer between FPGA and MATLAB

Lab-CTRL: System-wide control of data flow (start/ready signals, frame overlap)

Lab-ADC: ADC interfacing for audio sampling

Lab-PCB: Custom PCB design (microphone amplifier + anti-aliasing filters)

Lab-WINDOW: Hanning window application to sampled frames

Lab-FFT: Fast Fourier Transform using Vivado IP

Lab-MEL: Mel filter banks for feature extraction

Lab-DCT: DCT for compressing features

Lab-COMPARE: Euclidean distance–based digit classification

Lab-MATLAB: MATLAB simulations validating each processing step

All VHDL source files, test benches, and supporting documentation are provided, reflecting the challenges of analog circuit design, digital signal processing, and hardware verification required for a complete, real-time speech recognition system on FPGA.

