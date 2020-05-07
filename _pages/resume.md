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
* Pursuing: M.S. in Computer Engineering - University of California, Santa Cruz (Expected August 2019)

Work experience
======
__Undergraduate & Graduate Researcher__<br/><br/>
_University of California, Santa Cruz — May 2018 to Present_
* Implemented an algorithm which minimizes bitwidths of variables in hardware designs.
* Currently designing a bridge so FIRRTL/Chisel hardware designs can interface with a live synthesis/simulation framework called LiveHD. Goal is to leverage LiveHD so these designs can have immensely shorter synthesis and simulation times.

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
* RISC-V, Verdi, Vivado Design Suite, Yosys Open Synthesis Suite, TileLink, AMBA, Verilator Simulation Tool, Git, Unix, LaTeX
  
Notable Projects
=====
__RISC-V Pipeline__
* Created an in-order five stage pipeline in Verilog. It executes any instructions in the 32I/64I set. Used dhrystone as a testbench.
* After completion, used Yosys synthesis tool to optimize design.

__Multi-Server Password Cracker__
* Developed a C++ program that received a packet of hashed passwords then sent information to three other servers where they were to be solved. Also programmed each server with a multi-threaded algorithm that decoded up to 16 passwords at a time.
* All network communication was via TCP.
