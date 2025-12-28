# CMOS Standard Cell Library

![Platform](https://img.shields.io/badge/Platform-LTSpice%20XVII-red)
![Technology](https://img.shields.io/badge/Technology-CMOS-blue)
![Category](https://img.shields.io/badge/Category-VLSI%20%2F%20Digital%20Design-green)
![License](https://img.shields.io/badge/License-MIT-orange)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

## 📌 Project Overview

This repository documents the design, implementation, and simulation of a **Standard Cell Library** at the transistor level. 

The project focuses on building a robust collection of digital logic cells using **Complementary Metal-Oxide-Semiconductor (CMOS)** technology. Starting from fundamental primitives (NAND, NOR), the library expands to complex arithmetic circuits, serving as a foundational step for custom VLSI (Very Large Scale Integration) design.

All designs are created, simulated, and verified using **LTSpice XVII**.

---

## 🚀 Key Features

* **Transistor-Level Design:** Every gate is built from scratch using NMOS and PMOS transistor models, not behavioral abstractions.
* **Universal Logic:** Implementation of universal gates (NAND, NOR) to prove functional completeness.
* **Arithmetic Units:** Construction of Half Adders and Full Adders using hierarchical blocks.
* **Transient Analysis:** Comprehensive simulation waveforms verifying propagation delays and logic correctness.

---

## 📂 Modules & Progress

The repository is structured into modular directories. Click on the folder names below to view detailed documentation, truth tables, and schematics for each module.

| Module | Description | Status |
| :--- | :--- | :---: |
| **[📂 01_Logic_Gates](./01_Logic_Gates)** | Fundamental primitives including Inverter, NAND, NOR, AND, OR, and XOR. | ✅ Completed |
| **[📂 02_Arithmetic](./02_Arithmetic)** | Combinational arithmetic circuits including Half Adders and Full Adders. | ✅ Completed |
| **📂 03_Sequential** | Latches, Flip-Flops, and Registers. | 🚧 Planned |

---

## 🏆 Visual Showcase

Below is a preview of the **Full Adder** design, demonstrating the hierarchical integration of simpler gates into a complex arithmetic unit.

### Full Adder (1-bit)
*Combines XOR, AND, and OR gates to perform addition with Carry-In and Carry-Out.*

<table>
  <tr>
    <td align="center" width="50%"><b>Circuit Schematic (CMOS)</b></td>
    <td align="center" width="50%"><b>Transient Simulation</b></td>
  </tr>
  <tr>
    <td align="center"><img src="assets/FA_Circuit.png" width="100%"></td>
    <td align="center"><img src="assets/FA_Simulation.png" width="100%"></td>
  </tr>
</table>

*> **Note:** For a complete gallery of all gates and waveforms, please navigate to the respective folders listed above.*

---

## 🛠️ Tools & Technologies

* **Simulation Engine:** LTSpice XVII (High-performance SPICE simulator).
* **Modeling:** Standard NMOS/PMOS transistor models.
* **Verification:** Transient (Time-Domain) Analysis.

---

## 💻 Getting Started

To explore or modify these designs:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/VaradaGovind/CMOS-Standard-Cell-Library.git](https://github.com/VaradaGovind/CMOS-Standard-Cell-Library.git)
    ```
2.  **Open in LTSpice:**
    * Launch LTSpice.
    * Open any `.asc` file from the directories (e.g., `02_Arithmetic/Full_Adder.asc`).
3.  **Run Simulation:**
    * Click the "Run" (Running Man) icon.
    * Probe the Input/Output nodes to view the waveforms.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
