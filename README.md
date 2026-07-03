# 8Bit_ALU
#  8-Bit Arithmetic Logic Unit (ALU) using Verilog HDL

## 📌 Project Overview

This project implements an **8-Bit Arithmetic Logic Unit (ALU)** using **Verilog HDL** and verifies its functionality through a custom **testbench** in **Xilinx Vivado 2020.1**.

An Arithmetic Logic Unit (ALU) is one of the fundamental components of a processor, responsible for performing arithmetic and logical operations based on a control signal (`sel`). This project demonstrates the implementation of combinational logic, RTL design, and functional verification using Verilog HDL.

---

## 🚀 Features

The ALU supports the following operations:

| **Select (`sel`)** | **Operation**          |
| ------------------ | ---------------------- |
| `000`              | Addition (`A + B`)     |
| `001`              | Subtraction (`A - B`)  |
| `010`              | Bitwise AND            |
| `011`              | Bitwise OR             |
| `100`              | Bitwise XOR            |
| `101`              | Bitwise NOT (`~A`)     |
| `110`              | Left Shift (`A << 1`)  |
| `111`              | Right Shift (`A >> 1`) |

---

## 🛠️ Tools Used

* Verilog HDL
* Xilinx Vivado 2023.2
* Behavioral Simulation

---

## 📂 Project Files

* **alu.v** → ALU Design Module
* **alu_tb.v** → Testbench for Functional Verification

---

## 🧪 Verification

### Test Inputs

```
A = 20
B = 10
```

### Simulation Results

| **Operation** | **Result** |
| ------------- | ---------: |
| 20 + 10       |         30 |
| 20 - 10       |         10 |
| 20 AND 10     |          0 |
| 20 OR 10      |         30 |
| 20 XOR 10     |         30 |
| NOT 20        |        235 |
| 20 << 1       |         40 |
| 20 >> 1       |         10 |

All arithmetic and logical operations were successfully verified through behavioral simulation, and the obtained outputs matched the expected results.

---

## 📸 Screenshots

### RTL Design



### RTL Schematic



### Testbench



### Simulation Waveform



---

## 🎯 Project Summary

This project demonstrates the design and verification of an **8-Bit ALU** capable of performing eight essential arithmetic and logical operations using **Verilog HDL**. The design was implemented as a combinational circuit and verified through a custom testbench in **Xilinx Vivado 2020.1**, confirming the correct functionality of all supported operations through behavioral simulation.
