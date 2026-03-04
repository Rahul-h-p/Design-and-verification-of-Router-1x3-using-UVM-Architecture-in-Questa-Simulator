# Design-and-verification-of-Router-1x3-using UVM-Architecture-in-Questa-Simulator
Verifying the packet routing ability, parity checking, reset, sending packet and reading packet also tested the functional coverage and assertion successfully.
<br>
Router1x3 – RTL Design and UVM-Based Verification This repository showcases the RTL implementation and comprehensive verification of a Router1x3, a digital circuit component designed to route incoming data packets to one of three output ports based on address logic. The project is developed using Verilog HDL for design and UVM (Universal Verification Methodology) for structured, reusable verification.
<br>
Overview Router1x3 acts as a data traffic controller, intelligently forwarding packets of varying lengths to their designated output channels. The module interprets the destination address within the packet to determine the appropriate route.
<br>
🔧 Design Components FIFO (First-In-First-Out) Buffer: Temporary storage for packet data.
<br>
Synchronizer: Handles asynchronous clock domain crossing.
<br>
Register Block: Holds control and data fields.
<br>
Controller: FSM-driven logic to manage routing based on address decoding.
<br>
✅ Verification Highlights Universal Verification Methodology (UVM) testbench for scalable and modular verification.
<br>
Constraint-random test generation for wide functional coverage.
<br>
Assertions used to verify protocol compliance and catch corner cases.
<br>
Functional Coverage metrics implemented to ensure full feature testing and completeness of verification.
<br>
🧰 Tools & Environment Xilinx ISE: For simulation, synthesis, and analysis of RTL.
<br>
QuestaSim: Used for UVM simulation, debugging, and coverage analysis.
