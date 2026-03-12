# High-Fidelity Class AB Power Amplifier

## Overview
A multi-stage audio power amplifier designed for high linear gain and thermal stability. This project focuses on analog robustness, utilizing precision pre-amps and a Darlington output stage for high-current drive capabilities.

## System Architecture
* **Input Stage:** Utilizes **OPA134** high-performance audio operational amplifiers for low-noise pre-amplification.
* **Output Stage:** Features a **TIP41C/42C Darlington pair** for efficient power delivery.
* **Thermal Stability:** Implemented **diode-biasing** to prevent thermal runaway in the Class AB stage.

## Performance Summary
| Metric | Specification | Result |
| :--- | :--- | :--- |
| **Gain** | 75 dB (6206 V/V) | Validated via PSpice |
| **Input Sensitivity**| 1.55 µV | High Precision Detection |
| **Stability** | Thermal Biasing | Verified via Diode-Biasing |
| **Components** | E24 Tolerance | Verified via Monte-Carlo |

## Technical Skills Demonstrated
* **Simulation:** Monte-Carlo simulations in **OrCAD PSpice** for E24 component tolerance assessment.
* **Power Electronics:** Designing Darlington output stages and thermal compensation circuits.
* **Precision Audio:** Optimizing SNR and Gain in multi-stage signal chains.
