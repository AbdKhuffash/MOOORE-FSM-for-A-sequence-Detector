# MOOORE FSM for A sequence Detector

## Overview
This project focuses on implementing a Moore Finite State Machine (FSM) for sequence detection, specifically targeting the sequence "1011." Using T-Flip Flops and combination logic, the objective is to build a structural circuit capable of precisely detecting instances of the required sequence. A comprehensive testbench is developed to assess the performance of the design and identify potential errors, ensuring its dependability and usefulness. The successful completion of this project aims to showcase the efficient use of Moore FSM and digital logic design concepts.

## Introduction

Finite State Machines (FSMs) are mathematical models commonly used in computer programs to solve high-level control problems. In this project, a Moore FSM is utilized, where the output is determined solely by the current state, not by input events. The objective is to design a sequence detector using this model, with the sequence "1011" as the target.

## Design
#### Theoretical Design
The sequence detector for "1011" requires five states and three flip-flops to track the current state and transition based on input bits. The state transitions are controlled by T flip-flops equations derived from Karnaugh maps.

#### Verilog Implementation
The design is implemented in Verilog, utilizing T-Flipflops and logical gates to construct the sequence detector circuit. Test benches are developed to validate the functionality of the design.

## Results
The test benches yield expected results, confirming the correct operation of the sequence detector. Both structural and behavioral designs exhibit identical output waveforms, indicating their functional equivalence.

## Conclusion
The successful implementation of the Moore FSM sequence detector demonstrates the effective use of digital logic design concepts in detecting the target sequence "1011." This project showcases the versatility of FSMs in solving pattern recognition problems, with applications in various domains.

For detailed implementation and results, refer to the full project documentation provided in the repository.
