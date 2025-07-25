# Plant Health Monitoring System

A smart agriculture system using STM32 and TensorFlow Lite for real-time plant health monitoring and automatic irrigation control based on sensor feedback.

## Project Overview

This project aims to build a low-power embedded system that can monitor plant and soil health conditions and take automated actions to improve crop yield and reduce water usage. The system integrates multiple sensors over I2C, performs edge-based disease prediction using a lightweight machine learning model, and controls irrigation accordingly.

## Features

- Environmental monitoring using temperature, humidity, and soil moisture sensors
- I2C-based sensor communication with STM32
- Real-time disease detection using a TensorFlow Lite model
- Automatic irrigation control based on soil data and ML predictions
- Modular firmware in Embedded C
- Python scripts for training and converting the model to .tflite format

## Technologies Used

- STM32 Microcontroller (STM32F103 or similar)
- STM32CubeIDE for firmware development
- TensorFlow Lite for Microcontrollers
- Embedded C for real-time control
- Python for data preprocessing and ML model development
- I2C protocol for sensor communication
