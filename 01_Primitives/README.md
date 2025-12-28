# Primitive Logic Gates

This directory contains designs for fundamental digital logic gates implemented in this project. 

The designs below include their corresponding truth tables, circuit schematics, and functional simulation waveforms.

---

## 1. Inverter (NOT Gate)

A single-input gate that outputs the opposite logic level of its input. If the input is high (1), the output is low (0), and vice versa.

**Truth Table**
| Input (A) | Output (Y) |
| :---: | :---: |
| 0 | 1 |
| 1 | 0 |

**Results**
<table>
  <tr>
    <td align="center" width="50%"><b>Circuit Schematic</b></td>
    <td align="center" width="50%"><b>Simulation Waveform</b></td>
  </tr>
  <tr>
    <td align="center"><img src="../assets/Inverter_Circuit.png" width="100%"></td>
    <td align="center"><img src="../assets/Inverter_Simulation.png" width="100%"></td>
  </tr>
</table>

---

## 2. NAND Gate (Not-AND)

A universal gate that is the inverse of the AND gate. The output is low (0) only if all inputs are high.

**Truth Table (2-Input)**
| Input A | Input B | Output (Y) |
| :---: | :---: | :---: |
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

**Results**
<table>
  <tr>
    <td align="center" width="50%"><b>Circuit Schematic</b></td>
    <td align="center" width="50%"><b>Simulation Waveform</b></td>
  </tr>
  <tr>
    <td align="center"><img src="../assets/NAND_Circuit.png" width="100%"></td>
    <td align="center"><img src="../assets/NAND_Simulation.png" width="100%"></td>
  </tr>
</table>

---

## 3. NOR Gate (Not-OR)

A universal gate that is the inverse of the OR gate. The output is high (1) only if all inputs are low.

**Truth Table (2-Input)**
| Input A | Input B | Output (Y) |
| :---: | :---: | :---: |
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 0 |

**Results**
<table>
  <tr>
    <td align="center" width="50%"><b>Circuit Schematic</b></td>
    <td align="center" width="50%"><b>Simulation Waveform</b></td>
  </tr>
  <tr>
    <td align="center"><img src="../assets/NOR_Circuit.png" width="100%"></td>
    <td align="center"><img src="../assets/NOR_Simulation.png" width="100%"></td>
  </tr>
</table>
