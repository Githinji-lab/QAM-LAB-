# QAM-LAB-
# **256-QAM and QPSK Performance Analysis with OFDM Integration**  

## **Project Overview**  
This project explores the performance of 256-QAM and QPSK modulation schemes when combined with Orthogonal Frequency Division Multiplexing (OFDM) under varying noise conditions, including Additive White Gaussian Noise (AWGN) and phase noise. The study was conducted using MATLAB and Simulink, with performance metrics such as Bit Error Rate (BER), packet loss, and signal delay analyzed.  

## **Key Features**  
- Simulation of communication systems using 256-QAM and QPSK modulation techniques.  
- Analysis of channel impairments such as phase noise and AWGN.  
- Performance evaluation using constellation diagrams and BER curves.  
- Comparison between 256-QAM and QPSK in terms of data rate and noise resilience.  
- Implementation of OFDM for improved noise tolerance and reduced inter-symbol interference.  

## **Project Structure**  
- `analysis_of_256qam_report.pdf`: Detailed report on the study and findings.  
- `256qam_simulink_model.slx`: Simulink model used for the simulations.  
- `config_script.m`: MATLAB configuration script for setting simulation parameters.  
- `results/`: Directory containing simulation results and plots.  

## **Configuration**  
1. Open the Simulink model `256qam_simulink_model.slx` in MATLAB.  
2. Run the provided configuration script `config_script.m` to set up simulation parameters.  

### **Simulation Parameters**  
- FFT Size: 256  
- Cyclic Prefix Length: 16  
- Modulation Order: 256-QAM and QPSK  
- Noise Levels: Variable Eb/No and Phase Noise 
