# Design-a-Half-Adder-using-CMOS-transistor
To design a Half Adder using CMOS transistors on Cadence Virtuoso, implement XOR and AND gates using PMOS and NMOS transistors. The XOR output provides the sum, and the AND output gives the carry. Simulate and verify the functionality by applying all binary input combinations (00, 01, 10, 11).

# CMOS Half Adder Design Using Cadence Virtuoso

## Project Overview
This project demonstrates the design, simulation, and layout of a **CMOS Half Adder** using **Cadence Virtuoso** with the **GPDK90 technology library**. The design incorporates key steps, including schematic creation, simulation, and fabrication readiness.

---

## Objective
To design a Half Adder (EXOR-based) on the Cadence Virtuoso tool, ensuring functionality and manufacturability.

---

## Tools and Technologies
- **Cadence Virtuoso**
- **GPDK90 Technology Library**

---

## Design Flow
1. **Schematic Design**
   - Created the CMOS Half Adder schematic and generated a reusable symbol.
   
2. **Testbench Setup**
   - Simulated the Half Adder to validate its behavior and outputs.

3. **Simulation Results**
   - Performed transient and DC sweep analyses to measure Voltage Transfer Characteristics (VTC) and threshold voltage.

4. **Layout Design**
   - Designed the CMOS Half Adder layout adhering to GPDK90 specifications.

5. **DRC Check**
   - Verified compliance with fabrication rules through a Design Rule Check.

6. **LVS Check**
   - Ensured schematic-layout consistency with Layout Versus Schematic checks.

7. **GDSII File Generation**
   - Exported the final layout in GDSII format, ready for tape-out.

---

## Conclusion
The project successfully designed and verified a CMOS Half Adder. All design and simulation steps adhered to GPDK90 specifications, ensuring functional accuracy and manufacturability. The final design is ready for potential fabrication.

---

## How to Use
1. Clone this repository:  
   ```bash
   git clone <repository-url>


