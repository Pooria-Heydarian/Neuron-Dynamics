# Neuron-Dynamics
A Python-based simulation of neuronal models including LIF, ELIF, and AELIF, designed to explore and analyze the dynamic behavior of neurons under various input conditions. Ideal for researchers and enthusiasts in computational neuroscience.

 ![image](https://github.com/user-attachments/assets/2945cac3-d0df-40a0-8c39-f45dc38920a6)

## Overview
This project involves implementing various neuron models, including Leaky Integrate-and-Fire (LIF), Exponential Leaky Integrate-and-Fire (ELIF), and Adaptive Exponential Integrate-and-Fire (AELIF) using Python. The project aims to simulate these models under different input conditions to study their behavior and dynamics.

## Project Objectives
1. **Familiarization with Simulation Processes**: Gain experience in the implementation and simulation of computational models.
2. **Understanding Neuronal Dynamics**: Analyze the behavior of different neuronal models.

## Implemented Models
### 1. Leaky Integrate-and-Fire (LIF) Model
- **Description**: A simplified model representing neuron behavior by simulating how membrane potential changes in response to input currents.
- **Features**: Includes a basic LIF model and an enhanced version with a refractory period.

### 2. Exponential Leaky Integrate-and-Fire (ELIF) Model
- **Description**: An extension of the LIF model incorporating an exponential term to better capture neuronal dynamics.
- **Features**: Implemented with and without a refractory period for comparative analysis.

### 3. Adaptive Exponential Integrate-and-Fire (AELIF) Model
- **Description**: A more advanced model that includes an adaptation mechanism, making it suitable for modeling complex neuronal behavior.
- **Features**: Simulations with and without a refractory period.

## Simulation Details
The simulations involve applying various types of input currents to neuron groups, including:
- Constant current
- Step function current
- Sinusoidal function current
- Noisy constant current

Each model's response to these inputs is analyzed by observing changes in membrane potential, input currents, and spike events.

## Requirements
- Python 3.x
- Libraries: `PymoNNtorch`, `numpy`, `matplotlib`, `torch`, `random`
