# Hybrid Parallel Prefix Adder Using Han-Carlson and Ladner-Fischer Architectures

## About the Project

This project focuses on designing and analysing a Hybrid Parallel Prefix Adder that combines Han-Carlson and Ladner-Fischer architectures to improve carry computation in digital circuits.

The project explores conventional VLSI circuit design and reversible quantum computing to understand how adder logic can be implemented using different technologies.

## Objectives

* Design a hybrid parallel prefix adder.
* Compare different VLSI logic styles.
* Analyse power, delay, and area.
* Explore reversible logic using quantum gates.
* Understand the mapping of conventional Boolean logic into reversible circuits.

## Technologies and Tools

* **DSCH** – Digital circuit design
* **Microwind** – VLSI simulation and analysis
* **IBM Quantum Composer** – Quantum circuit design
* **Qiskit** – Quantum circuit implementation using Python

## Implementation

### 1. Conventional VLSI Design

Six logic styles are explored:

* CMOS
* Pass Transistor Logic (PTL)
* Double Pass Transistor Logic (DPTL)
* Gate Diffusion Input (GDI)
* Modified GDI (MGDI)
* Full Swing GDI (FSGDI)

Power, delay, and area are analysed to understand the performance differences between these logic styles.

### 2. Reversible Quantum Circuit

A 2-bit reversible adder is implemented and verified using IBM Quantum Composer and Qiskit.

The implementation explores reversible gates such as CNOT and Toffoli to represent arithmetic logic while preserving information about the inputs.

**Current status:** Initial implementation completed. Extending the reversible design to a full 4-bit hybrid adder is planned as future work.

## Key Learning Outcomes

* Understanding parallel prefix adder architectures.
* Comparing different transistor-level logic styles.
* Analysing VLSI circuit performance.
* Learning reversible logic and quantum circuit design.
* Mapping conventional arithmetic logic to reversible gates.

## Future Scope

* Extend the reversible implementation to a 4-bit hybrid adder.
* Perform further power, delay, and area analysis.
* Explore larger reversible arithmetic circuits.

## Conclusion

This project connects conventional VLSI design with reversible quantum computing and explores different approaches to implementing and analysing digital arithmetic circuits.

## Author

Electronics and Communication Engineering (ECE), Niharika Yarasu
