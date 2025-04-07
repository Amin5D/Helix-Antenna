# Helix Antenna for L-Band (1685.7 MHz)

This project documents the design, simulation, and fabrication of a 7-turn helical antenna for receiving L-band signals (1685.7 MHz) from the geostationary weather satellite AWS-G1.

## 📡 Overview

- Designed and simulated using **CST Microwave Studio**
- Achieved **16.4 dBi gain**, **<2 dB axial ratio**, and **36° beamwidth**
- Validated axial-mode behavior and impedance matching with jcoppens.com calculator
- Built using **1.5mm copper wire** and **3D-printed PLA/ABS spacers**
- Integrated with **HackRF One** and **LNA**, and tested using **SDR#** and **WXtoIMG**

## 🧪 Features

- CST Simulation files and far-field plots
- 3D printable spacer designs (.STL)
- Parts list and step-by-step hardware build guide
- SDR + decoding toolchain setup instructions
- PDF report with theory, implementation, and results

## 🖼️ Preview

![Antenna Simulation](images/simulation_results.png)
![Physical Build](images/antenna_build.jpg)

## 🧰 Requirements

- CST Microwave Studio (for simulation)
- SDR hardware (e.g. HackRF One)
- LNA (Low Noise Amplifier)
- SDR# and WXtoIMG (for signal reception)

## 📂 Directory Structure

See the folder descriptions above.

## 📜 License

This project is licensed under the MIT License. See `LICENSE` for details.

## 🙌 Acknowledgements

- CST Studio Suite
- jcoppens.com helix calculator
- SDR# and WXtoIMG for signal decoding
