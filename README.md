# Electronics-Simulation-of-ADC-and-DAC-in-PSpice

Design and Simulation Analysis of a **3-Bit Flash Analog-to-Digital Converter (ADC)** using PSpice. This project demonstrates the complete conversion process from an analog input signal to its corresponding 3-bit digital output through comparator-based flash ADC architecture.

## Project Overview

This repository contains the design, simulation, and analysis of a 3-bit Flash ADC, including:

- Flash ADC architecture using 7 comparators
- Resistor ladder reference voltage generation
- DC transfer characteristics
- Offset voltage analysis
- Comparator tolerance analysis
- Transient response and propagation delay analysis

## Files

| File | Description |
|------|-------------|
| `ADC_DC_Nominal.sch` | DC analysis under ideal conditions |
| `ADC_DC_Offset.sch` | ADC performance with comparator offset voltage |
| `ADC_DC_Tolerance.sch` | Effect of resistor/component tolerances |
| `ADC_Propagation.sch` | Propagation delay measurement |
| `ADC_Transient.sch` | Time-domain transient simulation |
| `README.md` | Project documentation |

## Flash ADC Specifications

| Parameter | Value |
|-----------|-------|
| Resolution | 3-bit |
| Number of Comparators | 7 |
| Architecture | Flash ADC |
| Simulation Software | OrCAD PSpice 9.2 |
| Reference Generation | Resistor Ladder |

## Simulations Performed

- **DC Sweep:** Digital output versus analog input
- **Offset Analysis:** Comparator offset effect on transition levels
- **Tolerance Analysis:** Influence of resistor variation on accuracy
- **Transient Analysis:** Real-time digital output switching
- **Propagation Delay:** Response time of comparator outputs

## Learning Outcomes

This project helped in understanding:

- Operation of Flash ADCs
- Quantization and digital encoding
- Reference voltage ladder design
- Comparator behavior under non-ideal conditions
- Practical simulation workflow in PSpice

git clone https://github.com/Saleh-EEE/Electronics-Simulation-of-ADC-and-DAC-in-PSpice.git
cd Electronics-Simulation-of-ADC-and-DAC-in-PSpice

## Software

- **OrCAD PSpice 9.2 (Student Version)**

## License

This project is licensed under the **MIT License**.
