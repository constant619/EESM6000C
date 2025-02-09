# Introduction
Lab 1 Vitis/Vivado Tools installation & Test
Student ID: 21139268
# Design Introduction
binary2bcd_double_dabble will get 8-bit binary input, then give 8-bit packed BCD outputs(00~99) and 16-bit unpacked BCD outputs(0000~0909).
The testbench should be time-independent, which means that the testing input should be independent of time, it should be an event trigger(in this lab, it's a clock trigger).
# Folder structure
Lab#1 – Vitis/Vivado Tools installation & Test/
| -- README.md       #overview of the project
| -- src/            #design sources, .v, tb
| -- report/         #rtl simulation log, synthesis log/resource, timing report
| -- LICENSE         # License file
# Build Setup
- Setup
  - TeraTerm/PuTTY/WinSCP Installation on PC/Laptop
  -Vivado Installation Including Vivado HLS on PC/Laptop
  - PYNQ with Jupyter Notebook (Host Program)
- Implementation
  - IP Design (Multiplier ) - Vivado HLS C/C++ to RTL
  - Generate Bitstream for FPGA - Vivado  RTL to Bitstream
  - Host Program - Jupyter Notebook

# Run test
After synthesis, this project just generates timing and utilizaiton report to confirm the background installation.

# HackMD submission: https://hackmd.io/@Ylitp/Lab1
