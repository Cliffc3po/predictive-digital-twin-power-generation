# Predictive Digital Twin for Power Generation using MATLAB/Simulink and LSTM

## Overview
This repository presents a predictive digital twin (DT) framework for turbine–generator systems, developed in MATLAB/Simulink. The approach integrates industrial SCADA/DCS data with machine learning to enable early fault detection and condition monitoring in power-generation assets.

## Key Features
- MATLAB/Simulink-based digital twin architecture  
- Integration with OPC-UA and MQTT data streams  
- Feature engineering (RMS, kurtosis, spectral energy)  
- LSTM-based time-series forecasting  
- Synthetic fault injection for validation  
- Residual-based anomaly detection and alarming  
- Designed for brownfield industrial systems (low-frequency SCADA data)

## Methodology
The digital twin follows a layered architecture:

1. Physical Plant  
2. Data Acquisition (OPC-UA / MQTT / CSV)  
3. Data Pre-processing and Feature Engineering  
4. Predictive Analytics (LSTM, Autoencoder, Random Forest)  
5. Visualization and Alarm Generation  

The framework is designed to operate using existing plant instrumentation without requiring additional sensors or infrastructure upgrades.

## Applications
- Predictive maintenance of turbine–generator systems  
- Vibration and thermal anomaly detection  
- Condition monitoring in legacy SCADA/DCS environments  
- Industrial digital transformation (Industry 4.0)

## Repository Structure
