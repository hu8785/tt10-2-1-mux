## How it works

This project implements a 2-to-1 multiplexer.

The inputs are:
- A
- B
- S (select)

The output is:
- O

When S = 0, the output O follows input A.  
When S = 1, the output O follows input B.

This is a combinational circuit where the output depends only on the current input values.

## How to test

Apply all combinations of inputs A, B, and S and observe the output.

| A | B | S | O |
|---|---|---|---|
| 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 |
| 0 | 1 | 0 | 0 |
| 0 | 1 | 1 | 1 |
| 1 | 0 | 0 | 1 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |
| 1 | 1 | 1 | 1 |

## External hardware

None

## Pinout

### Inputs
- ui[0] = A
- ui[1] = B
- ui[2] = S

### Outputs
- uo[0] = O
