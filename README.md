# Vexriscv_Stratix10
This repository contains the VexRISC-V implementation on Intel Stratix 10 FPGA board. 
Here, we optimize the VexRISC-V processor on Intel Stratix 10 FPGA board using HyperFlex optimizations techniques. 
The VexRiscv has the following features.
<ul>
  <li> Support the 32-bit RISC-V ISA(RV32IM). </li>
  <li> 5-stage "classic" RISC pipeline</li>
  <li>Optimized for Intel FPGA.</li>
    <li>The Instruction cache, Data cache.</li>
    <li>Support single cycle barrel shifter.</li>
    <li>Supports debug module, catch exceptions, dynamic branch, memory management unit(MMU).</li>
</ul>
The RISC-V core toplevel and other modules source code found in VexRiscv.v file,  the vexrisc_full.qsf is the Quartus setting file. 
The synthesis, place, route, and static timing analysis report found in the output_files/ directory. 
The synthesis results were obtained by synthesizing the VexRiscv.v on Intel Quartus Pro 2020.3 software tool with the fastest speed grade and Hyperflex Optimization techniques to get the maximum operating frequency.
<h3> Area utilization and maximum operating frequency of VexRisc-V on Intel Stratix 10 FPGA </h3>
<ul>
  <li> LUTs : 2222 </li>
  <li> Fmax : 291MHz</li>
</ul>