# Requirements

## Introduction
* The purpose of the project is to build a basic calculator based on Atmega328 microcontroller. This basic calculator which can perform Signed operations on 64bits numbers with max of two different math symbols or any number of operands but with the same math symbol. It uses 4×4 matrix keyboard. The result of calculation displayed on 16×2 LCD.   

* An LCD module can be interfaced with a microcontroller either in 8 bit mode or in 4 bit mode. 8 bit mode is the conventional mode which uses 8 data lines and RS, R/W, E pins for functioning. However 4 bit mode uses only 4 data lines along with the control pins. This will saves the number of GPIO pins needed for other purpose.
## Components Used
1.  4*4 Keypad Interface
2.  16*2 LCD Interface
3.  AVR Atmega 328 Microcontroller

## Software Used
1.  SimulIDE
2.  Visual Studio Code

## Cost and Feature
The cost of the hardware and software design is fixed and one-time investment only.

A calculator is a device that performs numerical operations. The features of this basic calculator can perform 
1.  Addition
2.  Subtraction
3.  Multiplication
4.  Division
## SWOT Analysis
### Strength
1.  The ultimate strength of calculators is its innovative and user-friendly.
2.  Calculators are long-lasting, and they have almost all kinds of basic numerical operations.

### Weaknesses
1.  The storage capacity is low to store the previous operations.
2.  Always power supply is needed for the calculator to perform an operation.
### Opportunities
1.  We can use a solar panel in calculators to reduce the power supply usage.
2.  We can add some additional advanced to it.
### Threats
1.  Nowadays people are not intrested in buying electronic calculator becuase calculator operations are implemented in our portable accessories like smartphones and laptops etc.

## 4W's and 1H
### Why
1.  To perform the basic numerical operations.
2.  To reduce the manpower.

### Where
1.  The calculator can be operated from anywhere.
2.  It can be used in our daily lives.

### Who
1.  Can be used by anyone is required to solve a numerical operation.
2.  Some provisional stores are using calculators for getting the accurate total amount. 

### When
1.  Anyone who have to solve a basic calculation.
2.  A person needs do a basic calculation in a fractions of second.

### How
1.  Giving different inputs we can find their desired output.
2.  The results of the calculators will be accurate than the manual calculations.

## Detail requirements
### High Level Requirements
| ID | Description | Status |
|----|-------------|--------|
| HLR_1 | Control Unit | Implemented |
| HLR_2 | Input Unit | Implemented |
| HLR_3 | Output Unit | Implemented |
| HLR_4 | Software Design | Implemented |

### Low Level Requirements
| ID | Description | HLR ID | Status |
|----|-------------|--------|--------|
| LLR_1 | AVR Atmega 328 Microcontroller | HLR_1 | Implemented |    
| LLR_2 | 4*4 Keypad Interface | HLR_2 | Implemented |
| LLR_3 | 16*2 LCD Interface | HLR_3 | Implemented |
| LLR_4 | Visual Studio Code & Simulide | HLR_4 | Implemented |
