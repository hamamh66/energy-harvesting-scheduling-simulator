# Energy Harvesting Scheduling Simulator

## Overview
This repository presents a reproducible simulation framework for evaluating scheduling policies in energy-harvesting communication systems. The simulator models stochastic energy arrivals, packet generation, and transmission decisions using discrete-event simulation (SimPy).

The framework enables systematic analysis of performance trade-offs between delay, throughput, packet loss, and delivery ratio under varying energy conditions.

---

## Key Features
- Discrete-event simulation using SimPy
- Multiple scheduling policies:
  - Greedy
  - Threshold-based
  - Randomized
  - Save-then-transmit
- Configurable energy arrival rates
- Performance metrics:
  - Average delay
  - Packets sent
  - Packets lost
  - Delivery ratio
- Automated visualization (bar plots + trend analysis)
- Reproducible experimental setup

---

## System Model
The simulation consists of three main components:

1. Energy Harvester  
2. Packet Generator  
3. Scheduler  

---

## Installation
pip install simpy pandas matplotlib

---

## Usage
python energy_harvesting_simulator.py

---

## Outputs
- CSV tables
- Plots
- Performance metrics

---

## Author
Habib Hamam and collaborators
