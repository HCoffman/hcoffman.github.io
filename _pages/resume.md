---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

If you would like to see this resume in a .pdf format: click [here](https://drive.google.com/file/d/15F-hsymGFM6HASOkN8agIjTwPvjxp1bG/view?usp=sharing)!

Education
======
* Earned:
  * M.S. in Computer Engineering - University of California, Santa Cruz (September 2020, GPA: 4.0)
  * B.S. in Computer Science, Minor in Computer Engineering - University of California, Santa Cruz (June 2019)

Work experience
======
__SOC Design Verification Engineer__<br/><br/>
_Apple — September 2020 to Present_
* (More specific details about my work in this role will be added in the future.)

__Undergraduate & Graduate Researcher (MASC Lab)__<br/><br/>
_University of California, Santa Cruz — May 2018 to September 2020_
* Served as one of the main contributors to the lab's open-source hardware compiler, LiveHD. 
  * Worked on a novel thesis that focused on bi-directionally translating multiple HDLs between one another to create a language-agnostic framework. (See the Notable Projects section below)
  * Implemented an algorithm which minimizes bitwidths of variables in hardware designs.

__Microprocessor Verification Engineer, Intern__<br/><br/>
_SiFive — June 2019 to September 2019_
* Verified the interaction between our cores and a new memory protection unit.
* Designed new verification infrastructure that leveraged the Verilog DPI interface to have C functions control signals internal to the core during simulation.
  
__Teaching Assistant: Microprocessor System Design, Computer Architecture__<br/><br/>
_Jack Baskin School of Engineering, UCSC — September 2019 to March 2020_
* Acted as a mentor for undergraduates, teaching them the fundamentals of microprocessor design leveraging C, hardware components, and inter-device communication.
* Taught students about computer architecture principles and pipelining techniques.
  
Skills
======
__Programming Languages:__
* Proficient: Verilog, C++, C
* Familiar: Chisel, Haskell, Python, Java

__Frameworks and Tools:__
* RISC-V, UVM, Verdi, AHB, APB, AXI, TileLink, Verilator Simulation Tool, Yosys Open Synthesis Suite, Git, Unix, LaTeX
  
Notable Projects
=====
__Thesis: Bridging Intermediate Representations to Achieve Hardware Design Language Translation__
* Designed and implemented novel translation techniques which bi-directionally map the FIRRTL intermediate representation (IR) to the LNAST IR. Used in the open-source hardware design framework, LiveHD.
* Created a process that translates from LiveHD's internal graph-like representation for a hardware design to its abstract syntax tree-like representation. This facilitated the translation between low-level HDLs like Verilog to abstract, open-source HDLs like Chisel or Pyrope.
* At the time of writing, this work performed at speeds between four to ten times faster than any other similar works.

__RISC-V Pipeline__
* Created an in-order five stage pipeline in Verilog. It executes any instructions in the 32I/64I set. Used dhrystone as a testbench.
* After completion, used Yosys synthesis tool to optimize design.
