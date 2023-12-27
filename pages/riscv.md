- https://riscv.org/wp-content/uploads/2017/05/riscv-spec-v2.2.pdf
- {{video https://www.youtube.com/watch?v=jOmWZbJoPCU}}
-
- # Subsets and Extensions
	- RV64G -> default target for compilers
- TDMgfy715#risc
- # Building a Riscv CPU
  https://learning.edx.org/course/course-v1:LinuxFoundationX+LFD111x+3T2022/home
-
- # RISC-V Course
  https://learning.edx.org/course/course-v1:LinuxFoundationX+LFD117x+3T2022/block-v1:LinuxFoundationX+LFD117x+3T2022+type@sequential+block@212f8f8499684c80ab82adff8f194c48/block-v1:LinuxFoundationX+LFD117x+3T2022+type@vertical+block@91cb35f1cf1843699d6437d8a0b98b6a
- # Hottes Riscv visualisierungs ding
  https://github.com/mortbopet/Ripes
-
- # RISC-V Manual
  https://github.com/riscv-non-isa/riscv-asm-manual/blob/master/riscv-asm.md
- # RISC-V specification
	- #riscv_interpreter
	- The RISC-V Instruction Set Manual comes in two volumes. Volume I: 
	  User-Level ISA contains general information about RISC-V, base 
	  instruction sets for 32, 64, and 128 integer architectures, standard 
	  extensions of the base instruction sets, and conventions. Generally 
	  speaking, the first volume covers all the necessary information to write
	   assembly user programs. User programs do not deal with so-called 
	  privileged functionality. Privileged functionality is required for 
	  programming operating systems or bare metal embedded systems. Thus, 
	  Volume II: Privileged Architecture covers information about these 
	  aspects and relevant extensions.
	- ## Volume 1
	  https://drive.google.com/file/d/1s0lZxUZaa7eV_O0_WsZzaurFLLww7ou5/view
		- There is no dedicated stack pointer or subroutine return address link register in the Base Integer
		  ISA; the instruction encoding allows any x register to be used for these purposes. However, the
		  standard software calling convention uses register x1 to hold the return address for a call, with
		  register x5 available as an alternate link register. The standard calling convention uses register
		  x2 as the stack pointer.
	- #riscv_interpreter
- https://five-embeddev.com/riscv-isa-manual/latest/rv32.html#rv32
- # Instruction Formats
  ![Instruction Formats](https://five-embeddev.com/riscv-isa-manual/latest/rv32_01.png)
-
-