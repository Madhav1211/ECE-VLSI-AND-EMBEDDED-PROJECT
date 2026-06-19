# 7-Segment Display Controller (Verilog)

## Objective
- Design a 7-segment display controller using Verilog HDL
- Convert 4-bit binary input into 7-segment output

## Tools Used
- Icarus Verilog
- GTKWave
- VS Code

## Working Principle
- Input is a 4-bit binary number
- Case statement is used as lookup table
- Output controls segments (a–g)
- Displays digits from 0 to 9

## Truth Table
| Input | Output |
|------|--------|
| 0 | 1111110 |
| 1 | 0110000 |
| 2 | 1101101 |
| 3 | 1111001 |
| 4 | 0110011 |
| 5 | 1011011 |
| 6 | 1011111 |
| 7 | 1110000 |
| 8 | 1111111 |
| 9 | 1111011 |

## Applications
- Digital clocks
- Calculators
- Elevators
- Scoreboards

## Conclusion
This project successfully converts binary input to 7-segment display output using Verilog.
