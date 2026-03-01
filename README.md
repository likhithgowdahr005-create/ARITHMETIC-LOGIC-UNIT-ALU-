# ARITHMETIC LOGIC UNIT (ALU)

**COMPANY:** CODTECH IT SOLUTIONS  
**NAME:** Likhith Gowda H R  
**INTERN ID:** CTISAR20  
**DOMAIN:** VLSI  
**DURATION:** 4 Weeks  
**MENTOR:** Neela Santosh  

---

## 📌 Project Overview

This project presents the design and simulation of a 4-bit Arithmetic Logic Unit (ALU) using Verilog Hardware Description Language (HDL). The ALU is a key component in digital systems and microprocessors responsible for performing arithmetic and logical operations.

The implemented ALU supports five operations: Addition, Subtraction, AND, OR, and NOT. A 3-bit select signal determines which operation is performed on the input operands. The design is verified using simulation and synthesized using Cadence Genus to analyze hardware performance including power, timing, and area utilization.

This project demonstrates the complete VLSI design flow from coding and simulation to synthesis and report analysis.

---

## 🎯 Objective

- Design a combinational ALU using Verilog HDL  
- Implement arithmetic and logical operations  
- Verify functionality using simulation waveform  
- Perform synthesis and analyze hardware performance  
- Understand practical VLSI design methodology  

---

## ⚙️ Tools Used

- Verilog HDL  
- Cadence Genus  
- SimVision  

---

## 🧮 ALU Operation Table

| Select (sel) | Operation |
|--------------|-----------|
| 000 | Addition |
| 001 | Subtraction |
| 010 | AND |
| 011 | OR |
| 100 | NOT |

The select signal controls the operation performed by the ALU and produces the corresponding output.

---

## 🖥 Simulation Output

![Waveform](Simulation_Output/waveform.png)

The waveform above verifies the functional behavior of the ALU. Different input combinations were applied through a testbench, and the output changes according to the selected operation, confirming correct implementation.

---

## 🔧 RTL Schematic (Synthesis View)

![RTL Design](RTL_Design/rtl.png)

The RTL schematic represents the synthesized hardware structure generated from the Verilog code. It illustrates the internal logic elements and confirms successful synthesis of the ALU design.

---

## 📊 Synthesis Reports

Power, timing, area, and gate-level reports are available inside the **Synthesis_Reports** folder.

---

## 📄 Project Report

📥 **Download Full Simulation Report:**  
[ALU Simulation Report (PDF)](Project_Report/ALU_Simulation_Report.pdf)

---

## ✅ Results

Simulation confirms correct execution of all arithmetic and logical operations. Synthesis analysis demonstrates efficient hardware utilization with acceptable power consumption and timing performance. The design successfully meets both functional and structural requirements.
