## How it works

This project implements a 2-to-1 multiplexer using two AND
gates, one NOT gate, and one OR gate. The select input S
determines which input is passed to the output Y.

When S = 0, Y = A.
When S = 1, Y = B.

The Boolean expression is Y = A'S + BS when the first
term uses the complement of S, expressed as A AND NOT S.

## How to test

Start the Wokwi simulation and toggle the first three
DIP switches.

Switch 1 controls input A.
Switch 2 controls input B.
Switch 3 controls select input S.

The output LED indicates the value of Y. Test all eight
input combinations to verify the multiplexer operation.

## External hardware

No external hardware is required for the logic circuit.
DIP switches and an LED are used for simulation and testing.
