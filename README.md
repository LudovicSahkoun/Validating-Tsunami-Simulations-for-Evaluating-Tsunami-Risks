# Validating Tsunami Simulations for Evaluating Tsunami Risks
Ludovic Sahkoun & Matthieu Lelarget (EURECOM)

## Introduction
Folder containing the code of the semester project: Validating Tsunami Simulations for Evaluating Tsunami Risks.
The project aims to simulate a tsunami in the region of Monaco in the south of France in order to study the associated risks.

In addition, we added the final report.

## Structure of the repository

The scratch contains data on the geographical area in which the simulation is carried out.

The directory Final Simulation is mainly composed by the following files:
  - setrun.py script which contains the code in charge of setting the parameters of the simulation
  - maketopo.py script which contains the code in charge of creating the fault
  - setplot.py script which contains the code to generate the different plots
  - _plots_ directory which contains all the resulting plots (empty before running the simulation)
  - _output_ directory which contains all the output files (empty before running the simulation)


## How to run the simulation
To run the simulation follow these steps:
  1. Open a terminal and navigate to the folder Final Simulation
  2. Execute the command _make new_
  3. Execute the command _make all_


