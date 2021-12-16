# OpenHWSpaces - A Weekly talk about Open Hardware at Twitter

This is a weekly open mic call inviting people to talk about themes regarding open-source hardware, FPGAs, toolchains, RISC-V and everything revolving around it.

Please send future topics via Issues, we also have discussions open.

## Topics

### 16/12/2021

- Yosys graphviz generation - visualizing you design: `yosys -p "read_verilog myfile.v; proc; opt; show -colors 2 -width -format dot -prefix MyModule -signed MyModule`, open file in <https://edotor.net>
- Chisel diagrammer - Visalize Chisel design in SVG <https://www.chisel-lang.org/diagrammer/>
- Nickolay's Chisel feedback - Chinese Academy of Sciences RISC-V Core <https://github.com/OpenXiangShan/XiangShan>
- Other HDLs (Chisel, nMigen - Amaranth HDL, SpinalHDL)
- Chisel Sync/Async reset - <https://www.chisel-lang.org/chisel3/docs/explanations/reset.html>
- Chisel Blackbox - Wrapping Verilog code in Chisel constructs - <https://www.chisel-lang.org/chisel3/docs/explanations/blackboxes.html>
- Hackster / Xilinx contest: <https://www.hackster.io/contests/xilinxadaptivecomputing2021>
- OpenSource toolchain - Symbiflow - Xilinx series 7 - <https://carlosedp.medium.com/xilinx-open-source-fpga-toolchain-on-docker-containers-93202650a615>

### 07/12/21

- Contributing to Open Source, how to start
  - Find some area of interest, things that you seem missing on projects you use or things that could be improved;
  - Documentation, it's usually the most lacking point of open source projects, create tutorials on how you started collecting resources used;
  - Contribute to SymbiFlow -  <https://symbiflow.github.io/developers.html>
  - Oleg's slides about contributing to FOSSi Foundation - <https://docs.google.com/presentation/d/1rpVZ76JY_Mj_1ESEYHpCV277n3SnGSjkdZTn2RIcEJE/edit#slide=id.g33e06a0ea3_0_0>
- Carlos's core, ChiselV written in Chisel HDL - <https://github.com/carlosedp/chiselv>
- LinuxFoundation course about building a RISC-V Core -<https://www.edx.org/course/building-a-risc-v-cpu-core>
- Kian's RISC-V Core created based on LF's course - <https://github.com/splinedrive/kianRiscV>
