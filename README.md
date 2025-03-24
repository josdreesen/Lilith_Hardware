# Lilith_Hardware
The ETH Lilith  computer hardware, described as a set of Kicad projects.

These TAR files are intended as a documenation of the ETH Lilith  modula-2 computer.
They are derived from the original ETH hardware documentation, and my own re-engeneering efforts.
They could potentially be used to recreate the Lilith, but in a project this size there will be errors.

The boards are : 
 - Backplane : a newly (i.e. 2025) designed backplane. Untested PCB layout included.
  - IFU  : instruction fetch unit
  - DRAM : memory boards ( minimum 2 required, and these 2 are populated different.)
  - ALU  : Aritmethic & logic unit, also barrekl shifter.
  - DSP  : display unit /  video board.
  - MCU  : microcontrol unit. Contains the AMD2901 microcode.
  - CDP  : Dataports and  IO circuitry.
  - DPU_NT : Optional debugging board. Verified PCB Layout included
  
  The original Lilith V1 also has a controller board for a Honeywell-Bull D120 Mididisk.
  The later Lilith V2 uses a WD1001-05 controller in combination with an IMI-5018 15Mb MFM harddisk.
  
  jos.dreesen@greenmail.ch
  
  
