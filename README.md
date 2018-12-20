# Mano-Basic-Computer-Using-VHDL
In this project the basic computer of M.Mano is implemented using VHDL.
Note that this project is still in progress and isn't complete yet.


-----------
/**
This is a draft file and it isn't well written so you might not catch a thing
consider studying Season 5 from the Book digital designe 2 by M. Mano*/
Project manoo computer with vhdl
Author: Erfan Soori
fall 97
supervisor :Mohsen Farhadi


##Schema:

![alt text](https://raw.githubusercontent.com/Asozusta/Mano-Basic-Computer-Using-VHDL/master/Screenshot%20(1).png)


	Faze 1:
	
		Control Unit:

		*reqs:


		0.parsing the instruction into two parts, the operand, and the operator.

		1.Decoder for instructions into microoperations.

		2.saving the operand in the Processing Register(Accumulator).

		3.16 operations , 4 corresponding bits.

		4.Processing Register = Accumulator(AC)

		5.Direct vs. Indirect addressing.

		6.Operations are performed on AC and operand contents.

		7.In a single operand operation instruction code the bits representing second operand can used for different purposes since there's no second operand.

		8.the most valuable bit in the addressing bits(I, short for Indirect) is required to determine the type of addressing.

		9.Indirect addressing requires the CU to perform two references against the memory.

		10.Effective address

		11.Destination Address

		12.Instructions are usually stored in a certain area of memory in a sequential form.

		13.CU requires a register to keep track of instructions and know which line of memory to read.The value for this register is incremental by 'one' unless there's a branch operation.(PC)12bits = referres to the next Instruction in the memory to be read after current instruction.

		14.CU requires a register to store instruction code after reading it from memory.(IR)16bits

		15.DR = dataRegister => keeping the operand read from memory.16bits

		16.AR = AddressRegister => keeping the address.12bits(2^12 = 4096 = memory size)

		17.In a branch operation the address part of the instruction is transferred to PC.

		18.if LD is 1 for a register then it gets the value ion the BUS in the next clk. for 12bit registers(AR and PC) the 4 most valuable bits are loaded as '0's weather they're being loaded on theselves or from them onto the BUS.

		19.if the 'write' input for the memory is set to 1 then memory writes the value on the BUS and if 'read' is set to 1 then it puts the value on the BUS.

		20. LD INR CLR

		21.Any register except for AC can recieve the value read from the memory.

		22.CU knows what to do from the 12to15 bit of the instruction.if 12to14 isn't 111 then it's a memory included operation an 15 will be the addressing type.

		23.CU creates the control signals for the registers

		24.


		BUS:

		0.It is a 3x7multiplexer to choose one between the output of the 7 parts we have at any given time.

		1.we can use AND to determine that.


		General:

		clk applies to every part of the system

		clk doesn't change the state of a register unless the register is enabled by a control signal.


		Memory:

		The data input and data output of the mem is connected to the BUS but the address input of the memory is connected to the AR.


		AC:
		gets data from a adder and locical circut







		CLK:

		In each clock cycle we can do two things at the same time:	

						1.put the content of any register on the BUS

						2.Perform an operation in the ALU

						the clock puls edge puts the bus value on the target register and the result of the ALU on the AC.

		Every timing in computer is up to this part.

		We should defenetly create this one.






```VHDL

		CU Main Parts:::


				1. 2 Decoders

				one 3X8 to decode the IR 12th to 14th bits into D0,D1...,D7 for the control gates.
				the other 4X16 for decoding the SC output into T0,T1,...,T15 for the control gates.


				2. 4bit SC = Sequence Counter

					counting from 0 to 15 constantly...output is decoded by one of the decoders

					Increment or Clear


				3. a number of gates 

						Inputs:

							0-11 from IR
							D0-D7 from IRDec
							I from I flipflop
							T0-T15 from TDec



				4. A flipflop (probably). Input from the 15th bit of IR


				5. 



```


		RAM:::

				AR can be a part of RAM OR it can be defined Seperately

