---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Earned: B.S. in Computer Science, Minor in Computer Engineering - University of California, Santa Cruz (June 2019)
* Pursuing: M.S. in Computer Engineering - University of California, Santa Cruz

Work experience
======
* May 2018 to Present: Undergraduate, Graduate Researcher
  * May 2018 to June 2019 (undergraduate), June 2019 to Present (Graduate)
  * University of California, Santa Cruz
  * Used C++ to upgrade a system that translated Verilog to in-house HDL Pyrope.
  * Currently implementing an algorithm to minimize bitwidths of variables in Verilog and Pyrope designs.

* June 2019 to September 2019: Microprocessor Verification Engineer, Intern
  * SiFive
  * Worked in Core Verification, focusing on verifying the interaction between our cores and a memory protection unit we designed for a very large customer.
  * Designed new verification infrastructure that leveraged Verilog DPI interface to have C functions control signals internal to the core.
  
* September 2019 to Present: Teaching Assistant (CSE 121)
  * Jack Baskin School of Engineering, UCSC
  * Act as a mentor for undergraduates, teaching them the fundamentals of microprocessor design leveraging C, hardware components, and inter-device communication.
  
Skills
======
* Programming Languages:
  * Proficient: Verilog, C++, C
  * Familiar: Chisel, Python, Java, Javascript
* Frameworks and Tools:
  * RISC-V, Verdi, Vivado Design Suite, Yosys Open Synthesis Suite, TileLink, AMBA, Verilator Simulation Tool, Git, Unix, LaTeX
  
Notable Projects
=====
* RISC-V Pipeline
  * May 2018
  * Created an in-order five stage pipeline in Verilog. It executes any instructions in the 32I/64I set. Used dhrystone as a testbench.
  * After completion, used Yosys synthesis tool to optimize design.

* Multi-Server Password Cracker
  * May 2018
  * Developed a C++ program that received a packet of hashed passwords then sent information to three other servers where they were to be solved. Also programmed each server with a multi-threaded algorithm that decoded up to 16 passwords at a time.
  * All network communication was via TCP.
