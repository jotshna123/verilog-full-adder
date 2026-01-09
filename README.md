# Full Adder – Verilog HDL

## Description
This project implements a 1-bit Full Adder using Verilog HDL.  
The design computes the sum and carry-out for three 1-bit inputs: A, B, and Cin.

## Functionality
- Sum = A ⊕ B ⊕ Cin
- Carry = (A & B) | (Cin & (A ⊕ B))

## Files Included
- `full_adder.v` – RTL design of the full adder
- `full_adder_tb.v` – Testbench for functional verification
- `wave_full.vcd` – Simulation waveform file
- Screenshots of GTKWave and Yosys synthesis (if included)

## Tools Used
- Icarus Verilog (iverilog)
- GTKWave
- Yosys (for synthesis and gate-level visualization)

## Verification
The design was verified through simulation using all possible input combinations.
Post-synthesis verification was also performed to ensure functional correctness.

## Author
Jotshna Tulasi
