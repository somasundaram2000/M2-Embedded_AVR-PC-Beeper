## 8x8 LED Matrix :

## Code Badges :
 Build| Cppcheck | Codacy
----|----|-----|
[![Build Status](https://github.com/somasundaram2000/M2-Embedded_AVR-PC-Beeper/actions/workflows/compile.yml/badge.svg)](https://github.com/somasundaram2000/M2-Embedded_AVR-PC-Beeper/actions/workflows/compile.yml)|[![Cppcheck](https://github.com/somasundaram2000/M2-Embedded_AVR-PC-Beeper/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/somasundaram2000/M2-Embedded_AVR-PC-Beeper/actions/workflows/cppcheck.yml)|[![Codacy Badge](https://api.codacy.com/project/badge/Grade/7a5a74c903084ddfa1a4dc38ef3b2716)](https://app.codacy.com/gh/somasundaram2000/M2-Embedded_AVR-PC-Beeper?utm_source=github.com&utm_medium=referral&utm_content=somasundaram2000/M2-Embedded_AVR-PC-Beeper&utm_campaign=Badge_Grade_Settings)|

[![code quality](https://api.codiga.io/project/30265/score/svg)](https://app.codiga.io/project/30265/dashboard)
[![code grade](https://api.codiga.io/project/30265/status/svg)](https://app.codiga.io/project/30265/dashboard)


## Introduction :
- A 8x8 LED Matrix interfacing is used to display the English characters. 
- In 8x8 LED Matrix there will be 64 I/O pins for displaying each diode pixel.
- In 8x8 LED Matrix, all the anodes are connected together in R1 to R8 and cathodes are connected together in columns C1 to C8.


## SWOT Analysis : 
### Strengths :
- Power saving.
- Long service life.
- Cost advantage.

### Weakness :
- Difficulty in maintaining.
- To perform this operation, power supply is always needed.

### Opportunities : 
- To interface an Arduino Uno board with an 8x8 LED Matrix to display information.

### Threats :
- Chip will be damaged because of too much current.


## 4W's and 1H :
### Why :
- A 8x8 LED Matrix is used to display the information.

### Where :
- It is used to interface Microprocessors and microcontrollers with LEDs.

### Who :
- Can be used as a reference for 8x8 LED Matrix.

### When :
- To display the information in different styles.
- Used to display Speed limits.

### How :
- It is a grid of lights arranged in rows and columns.
- All the anodes are connected together in R1 to R8 and cathodes are connected together in columns C1 to C8.


## Detail Requirements :
### High Level Requirements :
|ID | Description | Result
|--------|-------------|-------------
| HLR1 | Input Unit | Implemented         
| HLR2 | Output Unit | Implemented
| HLR3 | Software Design | Implemented


### Low Level Requirements
| ID | Description | Status |
|----|-------------|--------|
| LLR1 | AVR Atmega 328 Microcontroller | Implemented |    
| LLR2 | 8x8 Matrix LED | Implemented |
| LLR3 | Visual Studio Code & Simulide | Implemented |


# Test Plan

|Test ID | Description | Input | Exp O/P | Actual O/P |
|--------|-------------|---------|------------|--------
| ID 01 | Power ON | Display ON | Power | SUCCESS  
| ID 03 | User input | Input given | Input Value | SUCCESS
| ID 02 | Return Output | Input value by user | Shows Output in Display | SUCCESS


