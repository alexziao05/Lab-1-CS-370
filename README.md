# Lab 1 - Digital Logic Circuits
## CS 370 - Computer Architecture

**Group Members:**
- Alex Huang
- Mateen Rahbar  
- David Soriano
- Bryce Rambach

## Overview

This lab focuses on implementing and understanding fundamental digital logic circuits using LogicWorks 5. The project includes the design and construction of multiplexers and basic logic gates, providing hands-on experience with digital circuit design and Boolean logic.

## Project Contents

### Main Files
- `lab1 (FILE OPEN THIS FIRST).clf` - Primary LogicWorks library file (open this first)
- `Lab1 Testing Area.cct` - Testing environment for circuit validation

### Circuit Implementations
- `2-1 Mux.cct` - 2-to-1 Multiplexer implementation
- `4-1 Mux.cct` - 4-to-1 Multiplexer implementation

### Documentation
- `Helpful Diagrams/` - Contains reference materials:
  - `Circuit Diagram (AND - OR) Gates.png` - Logic gate reference
  - `Low Tri State Buffer Truth Table.png` - Tri-state buffer specifications
  - `Truth Table 4-1 Mux.jpeg` - 4-to-1 multiplexer truth table

## Getting Started

### Prerequisites
- LogicWorks 5 software
- Basic understanding of digital logic and Boolean algebra

### Opening the Project
1. Launch LogicWorks 5
2. Open `lab1 (FILE OPEN THIS FIRST).clf` as your starting library
3. Use `Lab1 Testing Area.cct` for testing your implementations
4. Reference the diagrams in `Helpful Diagrams/` for circuit specifications

### Circuit Descriptions

#### 2-to-1 Multiplexer (2-1 Mux.cct)
- **Inputs:** 2 data inputs (A, B), 1 select line (S0)
- **Output:** Single output that selects between inputs based on select line
- **Function:** Output = A when S0=0, Output = B when S0=1

#### 4-to-1 Multiplexer (4-1 Mux.cct)
- **Inputs:** 4 data inputs, 2 select lines (S0, S1)
- **Output:** Single output that selects one of four inputs
- **Function:** Uses 2-bit select code to choose from 4 input lines

## Learning Objectives

- Understand multiplexer functionality and applications
- Practice digital circuit design using LogicWorks
- Implement Boolean logic using AND, OR, and NOT gates
- Analyze truth tables and circuit behavior
- Gain experience with computer-aided design tools for digital circuits

## Lab Instructions

1. Start by examining the truth tables provided in the `Helpful Diagrams/` folder
2. Open the main library file to access component libraries
3. Implement the required multiplexer circuits
4. Test your implementations using the provided testing area
5. Verify functionality against the provided truth tables

## Notes

- All circuit files use LogicWorks 5 format (.cct)
- Keep reference to the truth tables when designing circuits
- Test thoroughly before submission

## Troubleshooting

- Ensure LogicWorks 5 is properly installed
- Check that all library paths are correctly set
- Verify circuit connections match the truth table requirements
- Use the testing area to validate circuit behavior

---

*This lab is part of CS 370 - Computer Architecture coursework focusing on digital logic fundamentals.*