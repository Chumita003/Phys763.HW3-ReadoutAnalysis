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

## Results

**Readout state discrimination (IQ plane).** For each qubit, ground- and excited-state single-shot measurements are rotated into the I quadrature and separated by an optimal threshold, from which the readout confusion matrix and fidelity are computed (Problem 2, datasets 65 and 71).

![Readout IQ discrimination](figures/readout_iq_discrimination.png)

**T₁ relaxation fits.** Excited-state population versus delay is fit to a decaying exponential for each working qubit to extract T₁. The values are compared across datasets 58 and 70 to quantify the performance change produced by the qubit tune-up between experiment days (Problems 3–4).

![T1 decay fits](figures/t1_decay_fits.png)

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

## Skills Demonstrated 
- Quantum readout analysis using Python and xarray
- Signal discrimination and fidelity benchmarking
- Curve fitting with scipy and interpretation of T₁ decay
- Calibration comparison using machine state JSON files
- Data visualization with matplotlib

---

## Repository Contents

This repository is a **writeup**: it presents the methodology, key figures, and physical interpretation of the analysis. It intentionally does **not** include the full solved notebook or the graded report, which are withheld to respect PHY 763 academic-integrity guidelines on publishing coursework solutions.

The analysis relies on experimental datasets and calibration infrastructure from the **QOLab / Qualibrate environment used in PHY 763**, which are not publicly accessible; the `data` directory is therefore excluded as well.

**The complete solved notebook and graded report are available upon request** — feel free to reach out through my GitHub profile.

---

## License

The code and written analysis in this repository are released under the MIT License (see `LICENSE`). This applies to the author's own code and analysis only — the experimental datasets referenced remain the property of the PHY 763 course and are not redistributed here.
