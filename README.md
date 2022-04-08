# Impact of Noise in Quantum Circuits (ELEC0118_21_22)
* This is a research project done by EEE fourth-year students Yansong Huang and Ben Han Li. <br>
* The project aims at studying the impact of noise in quantum circuits. <br>
* Four types of noise models (measurement noise, depolarising noise, reset noise, thermal relaxation noise) have been chosen and were applied to four quantum circuits (XOR circuit, quantum teleportation circuit, Bernstein-Vazirani circuit, quantum Fourier transform circuit). <br>
* The whole program is written in Python. <br>

## File Organisation:
#### 1. `NoiseModels.ipynb`: <br>
This file contains the process to create the four quantum circuits, build four types of noise models and apply noise models to the circuits.<br>
#### 2. `ThermalModels.ipynb`: <br>
This file contains the process to create and apply individual thermal noise models to the four circuits.<br>

## The necessary Python packages/modules are: <br>
`Qiskit 0.31.0`, `numpy 1.20.3`, `matplotlib 3.5.0` <br>
When downloading the packages/modules above, other essential packages/modules will be downloaded automatically as dependencies.

## To run the code, please follow the steps below: <br>
1. Download the repository (either by doing `git clone` or downloading zip) and make sure you have installed `Jupyter Notebook`. <br>
2. Open `NoiseModels.ipynb` or `ThermalModels.ipynb` in `Jupyter Notebook`. <br>
3. Run the code cells from top to bottom (by pressing `Shift` and `Enter` at the same time). <br>
4. You will see circuit diagrams and simulation results showing as histograms and line charts. <br>
