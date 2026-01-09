# Full Adder – Verilog HDL

## Overview
This project implements a **1-bit Full Adder** using **Verilog HDL**.  
The design is verified through **RTL simulation**, **logic synthesis**, **gate-level netlist generation**, and **post-synthesis verification**.

## Files and Structure
- **Design code/**  
  Verilog RTL implementation of the Full Adder

- **Testbench/**  
  Testbench used for functional verification

- **full_adder_simulation.png**  
  RTL simulation waveform (GTKWave)

- **full_adder_wave.png**  
  Output waveform showing sum and carry

- **full_adder_syn1.png, full_adder_syn2.png**  
  Synthesized RTL schematic

- **full_adder_netlist1.png, full_adder_netlist2.png**  
  Gate-level netlist representation

- **full_adder_postverification.png**  
  Post-synthesis verification result

- **full_adder_postver_wave.png**  
  Post-synthesis waveform

- **full_adder_diagram.png**  
  Functional block diagram of Full Adder

## Tools Used
- Icarus Verilog (iverilog)
- GTKWave
- Yosys (for synthesis and netlist generation)

## Functionality
The Full Adder performs binary addition of three 1-bit inputs:
- Inputs: `a`, `b`, `cin`
- Outputs: `sum`, `cout`

## Status
✔ RTL design completed  
✔ Simulation verified  
✔ Synthesis completed  
✔ Post-synthesis verification completed
