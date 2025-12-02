# Wireless Channel Simulator

Monte Carlo simulation comparing BPSK, QPSK, and 16-QAM modulation schemes over AWGN and Rayleigh fading channels.

**Author:** Nidhi Bhatt  
**Institution:** Indira Gandhi Delhi Technical University for Women  
**Program:** B.Tech Computer Science and Engineering

---

## Overview

Simulates and analyzes the Bit Error Rate (BER) performance of digital modulation techniques in wireless communication systems.

---

## Features

**Modulation Schemes:**

- BPSK - 1 bit/symbol (most robust)
- QPSK - 2 bits/symbol (medium efficiency)
- 16-QAM - 4 bits/symbol with Gray coding (highest data rate)

**Channel Models:**

- AWGN - Ideal baseline with additive noise
- Rayleigh Fading - Realistic multipath with Perfect CSI

**Analysis:**

- BER vs SNR performance curves
- Constellation diagrams (2×3 grid)
- 100,000 bits per test point
- SNR range: 0-20 dB (2 dB steps)

---

## Technologies

- Python 3.x
- NumPy
- Matplotlib
- SciPy

---

## Installation

```bash
pip install numpy matplotlib scipy
```

---

## Usage

Run all cells sequentially in Jupyter Notebook:

1. Import libraries
2. Define modulation functions
3. Define channel models
4. Define demodulation functions
5. Define BER calculation
6. Run complete simulation (takes time)
7. Generate BER plots
8. Generate constellation diagrams
9. Display summary report

---

## Results

### Performance at 10 dB SNR

**AWGN Channel:**

- BPSK: 0.08% BER
- QPSK: 0.08% BER
- 16-QAM: 7.80% BER

**Rayleigh Fading:**

- BPSK: 2.26% BER
- QPSK: 4.40% BER
- 16-QAM: 14.07% BER

### Output Files

- `Complete_BER_Analysis.png` - BER vs SNR curves
- `All_Constellations.png` - Constellation diagrams

---

## Key Insights

- BPSK most robust, lowest data rate
- 16-QAM highest throughput, less robust
- Rayleigh fading significantly degrades performance

---
