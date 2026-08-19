# Proteus-Barking-sensor---Task-1-Maker-intern-
LM324 Analog Signal Conditioning & Voltage Ladder Circuit
This repository contains the design, Proteus simulation, and hardware validation for a multi-stage analog signal processing circuit built around the LM324 Operational Amplifier.
The circuit takes a continuous analog input signal 0V -> 5V, amplifies it through a non-inverting op-amp stage, and passes it through a resistive divider ladder to trigger four sequential comparator outputs as the input voltage rises.
Key Features
Non-Inverting Amplification Stage: Scales incoming low-level analog signals for processing.
Multi-Stage Window Comparator Ladder: Sequentially triggers discrete outputs based on calibrated voltage thresholds.
Modular Sensor Support: Interfaces directly with 3-pin analog transducers (e.g., Sharp IR distance sensors, TEMT6000 light sensors) or a $10\text{ k}\Omega$ potentiometer for manual bench testing.
Proteus Simulation: Complete schematic and simulation files included for virtual testing before PCB layout.
