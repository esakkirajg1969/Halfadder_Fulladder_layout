# Half Adder and Full Adder – CMOS Schematic and Layout Design

## Project Overview

This project covers the transistor-level schematic design, physical layout implementation, and verification of **Half Adder** and **Full Adder** circuits using **Synopsys Custom Compiler**. The designs were implemented using the **SAED 32 nm PDK** and verified using **Synopsys IC Validator (ICV)**.

The project demonstrates the complete custom-design flow, from schematic creation to physical layout and verification.

## Tools and Technology

| Item | Details |
|---|---|
| Schematic design | Synopsys Custom Compiler |
| Physical layout | Synopsys Custom Compiler |
| Verification | Synopsys IC Validator (ICV) |
| Technology | SAED 32 nm PDK |
| Design type | Transistor-level CMOS |
| Verification checks | DRC, LVS, and extraction |

---

# 1. Half Adder Design

A Half Adder is a combinational logic circuit that adds two 1-bit binary inputs.

### Logic Function

- **Inputs:** A, B
- **Outputs:** Sum, Carry

**Boolean expressions:**

- `Sum = A XOR B`
- `Carry = A AND B`

## Half Adder Schematic

The transistor-level schematic was created using Synopsys Custom Compiler.

![Half Adder Schematic](images/halfadder_schematic.jpeg)

## Half Adder Layout

The corresponding CMOS physical layout was implemented in Synopsys Custom Compiler using the SAED 32 nm PDK.

![Half Adder Layout](images/Halfadder_layout.jpeg)

## Half Adder Verification

The design was verified using Synopsys IC Validator.

- **DRC:** Clean
- **LVS:** Pass
- **Extraction:** Clean

![Half Adder Verification](images/Halfadder_verification.jpeg)

---

# 2. Full Adder Design

A Full Adder is a combinational logic circuit that adds three 1-bit inputs: two operand bits and a carry-in.

### Logic Function

- **Inputs:** A, B, Cin
- **Outputs:** Sum, Cout

**Boolean expressions:**

- `Sum = A XOR B XOR Cin`
- `Cout = (A AND B) OR (Cin AND (A XOR B))`

## Full Adder Schematic

The transistor-level schematic was created using Synopsys Custom Compiler.

![Full Adder Schematic](images/Fulladder_schematic.jpeg)

## Full Adder Layout

The corresponding CMOS physical layout was implemented in Synopsys Custom Compiler using the SAED 32 nm PDK.

![Full Adder Layout](images/Fulladder_layout.jpeg)

## Full Adder Verification

The design was verified using Synopsys IC Validator.

- **DRC:** Clean
- **LVS:** Pass
- **Extraction:** Clean

![Full Adder Verification](images/Fulladder_verification.jpeg)

---

## Verification Summary

| Design | DRC | LVS | Extraction |
|---|---|---|---|
| Half Adder | Clean | Pass | Clean |
| Full Adder | Clean | Pass | Clean |

## Project Highlights

- Transistor-level CMOS schematic design.
- Physical layout implementation of Half Adder and Full Adder circuits.
- Hands-on experience with Synopsys Custom Compiler.
- Physical verification using Synopsys IC Validator.
- Successful DRC and LVS verification, with clean extraction results.

## Repository Structure

```text
Half_Adder_Full_Adder/
├── images/
│   ├── halfadder_schematic.jpeg
│   ├── Halfadder_layout.jpeg
│   ├── Halfadder_verification.jpeg
│   ├── Fulladder_schematic.jpeg
│   ├── Fulladder_layout.jpeg
│   └── Fulladder_verification.jpeg
└── README.md
```

## Conclusion

Successfully completed the schematic design, CMOS physical layout implementation, and verification of Half Adder and Full Adder circuits using Synopsys Custom Compiler and IC Validator with the SAED 32 nm PDK. Both designs achieved **DRC Clean, LVS Pass, and clean extraction results**.

---

# Author

**Esakkiraj G**
B.E. Electronics and Communication Engineering
Custom & Analog Layout Trainee

**Domain:** VLSI | Custom Layout | Analog Layout | CMOS Design
