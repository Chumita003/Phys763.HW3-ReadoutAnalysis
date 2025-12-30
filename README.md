# Phys763.HW3 – Readout Analysis

This repository contains a **coursework assignment** developed as part of **PHY 763** at the University of Wisconsin–Madison.

The work focuses on the **analysis and physical interpretation of experimental qubit readout data** obtained from a superconducting qubit platform.  
All datasets used in this repository were **provided by the course instructors** for educational purposes.

---

## Context

This notebook corresponds to **Homework 3** of PHY 763 and is **not an independent research project**.  
The goal of the assignment was to develop intuition for experimental limitations in qubit readout rather than to optimize software performance.

---

## Objectives

The analysis aims to:

- Examine dispersive qubit readout signals from experimental data
- Study signal-to-noise ratio (SNR) behavior
- Evaluate readout fidelity and its dependence on experimental parameters
- Identify physical limitations arising from relaxation processes (e.g., T1 decay)
  
---

## Data Disclaimer

All experimental datasets included in this repository:

- Were **provided by the PHY 763 instructional staff**
- Are used **strictly for educational analysis**
- Do **not** represent original data collected by the author

The analysis and interpretation of the data were performed independently by the author as part of the coursework.

---

## Learning Outcomes

Through this assignment, I developed experience in:

- Analyzing experimental readout data from superconducting qubits
- Interpreting signal-to-noise scaling and its impact on readout fidelity
- Connecting experimental observations to physical processes such as relaxation (T1)
- Working with real hardware datasets using Python and Jupyter notebooks

---

## Usage

To run the notebook locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Chumita003/Phys763.HW3-ReadoutAnalysis.git
   cd Phys763.HW3-ReadoutAnalysis
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Make sure the data/ folder is located in the same directory as the notebook (Phys763_HW3b.ipynb), since the analysis scripts load datasets directly from data/.

4. Launch Jupyter Notebook:
   ```bash
    jupyter notebook Phys763_HW3b.ipynb

5. Run all cells to reproduce the analysis:/n
   The notebook will generate plots of IQ blobs, confusion matrices, and T1 decay fits using the provided datasets.
