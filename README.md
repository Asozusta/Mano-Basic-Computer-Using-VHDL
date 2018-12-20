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

![alt text](https://www.draw.io/?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Untitled%20Diagram.html#R7V3Zcts4Fv0aV808WIWF2B4dOUmnYmdccdKdzJsi0bYmiuiW6djprx9QJChioRaKIOFI6qqOBZGghHvuuQsugBM8%2FPH8djG6v7tMJvHsBIHJ8wk%2BP0EIyv%2FkP1nLr7yFYpE33C6mk%2BKiVcP19J%2B4aARF6%2BN0Ej9oF6ZJMkun93rjOJnP43GqtY0Wi%2BRJv%2BwmmelPvR%2FdxlbD9Xg0s1v%2Fmk7Su7yVI7pq%2FyOe3t6pJ0Na%2FL5vo%2FH320XyOC%2Bed4LwzfKVf%2FxjpPoqfujD3WiSPFWa8OsTPFwkSZr%2F9eN5GM%2BysVXDlt%2F3pubT8nsv4nm6zQ0kv%2BHnaPZY%2FPRXn6%2BLr5b%2BUsMhv%2BV99uf9IhnHD3JsXz3dTdP4%2Bn40zpqfJAhk22g2vZ3Lt2P57HghG37Gi3QqB%2FWs%2BODHdDLJunz1kAscDEDEiHx%2Fk8zT6%2BJxMPs8XSTfy5HH2RXT2WyYzJLF8gvhN2%2BG8iXbF0k6SqdJ1jtQHeWdR9n728VoMpVfR906T%2BbZ8%2B1RKgYu%2B8bxc6WpGLW3cfIjThe%2F5CXq06iQ4C%2F1XkH8aQUYSHFx1Z2GFl4gtUDpbdn7SlLyj0JYNZKOLMkN5Y9fJNlFn%2BfT1BJiI5GlyX0T%2BcRwQmKmC4SA8s7KlYIyPKLtyAQbMqHclghkLolgjPYXyeXp0%2Fjq8e724vYcvPpEP119OQenEFBLUJej6Vy2lPJqQ1ClbjXQpUybHMrTgkQiTDSJEEEskVDkkAhlxJtAmCWQ89eyLyknDLPfHT1DWnnbt3xubmI6HuvyQU5dmjDxDQCbFSfThTSS%2Bft5ssge1AoFIoAHunwxJQNbwkhpl6ZzoAUWrJGwbdWGs2T8XTa9jefxYpTKEetZqpNRzG%2B2kiod8%2FjbTTsio2rQldVCgjkEBpXaVgXGqDd5cUte0bfMgoHr%2BO%2FHeC5FkrHl41IIByk3iJR3oQSnHAvN24AONVP2rn2xYWiJbXjx3hKQ%2FInyu7y6S3%2FMtEE2fLLqOBdN24vRBYKlFx5PbM8QtWTcpMtn%2BIA8GnBceUFLRpHD1iF%2FEkKWhF6se38qunXwTwlFmnQZscUJCfTl4NdI1DZtH88uayU6zUQ1H82upcVbhrxOyVZUcxW%2F%2FucxnU3nSmQ142yKY5kBoMu%2FslGjuCVNE0jXNIZs%2BotcfmQEvVktbFuts4%2BncJkFmKYPlkxWfAQ3y2HL8W5lbJVDrFiMQpdPECFsD6%2ByOO2PLsHW6J5%2F7GRM1zjP8eghbckRMwIjKQWHsXBlD6g3a0FsQMswaJYWY3SSpdsURdO%2FH5N8KDBYvqpN9Db7951UBqo6kN8o7yP%2FbD9BmhIbLcbFW0m8ljF5JV6DM%2BL00MBIQJWl0CKuZcbOSwQMo20jYG9yVj1rcjbkEc8nZ1keNbP3s9HDw3S8zoXLMj4ERsBloXVjHzlyRerO%2BHmafsn9BsSL91%2Bz5w0AxsX7q3gxlcOQ%2BR9L7ZSCWfxSNxHV8DVvAEg1mLfVCvYheVyM43Wjp7QkHS1u43TdlSrzE0%2B0ZLMNlQoUiAMJqm0RzyQx%2FdRT1C54FE%2B4SqZLrVVIpJGGROm86F3kv724C1VyxmZHRHeMiDCSZ%2FnQWB0t0Vr%2B7H0AbAce7z6ekFfyB5FzC8rBxR9tWW5MdKcIMUdM6PJPsT9qsQMOPbeGn%2FnLTq21YRK4kTRz%2BlvYZRQgQN5EZ08otGgVHFbAUIgKk%2Bs8vsZi1ApjMzkrpAZCzjTSMYGUU74rOVNidmSwvHdytiPUnJwjSc6n%2BZ%2FooHiaQEMkEXUlyV3o8pcaYnZ81a26l84eqbp6TZR9s88WmrIjHRClQdhZ2Q3WoF0rO7OVvS%2BjwSyrsYIY6wBjLzYuENRAowmibdEIgUF0mHQNR3uuPTc4sLQ94KBMDzdCBBzxAEyPnWc6l5KZZDLK%2FmAHJSISsYFpDrBrTpY75mQjbxMN3It%2FgMd8R%2F8ADgCIKuydTSqJmmSQyerqaRnRqrgwnn1Lnl6vGvah%2FMCIHAJD2yk0dHhrJkdYrxOwspE1TC7hMPpVuew%2Bu%2BBhzVc2y%2BgiotUryj%2FyLtu1E9xLrLsDuEu3Rc9YLjOYjVBcVReuqwsiNerSAvK3cHZ4UDoimI43IhqriJoPK9OpJY%2B3riTG7CfmnSiJy7fXpoNW2qLmfrIPTvPp%2FzN5gUTXsz0xNLz4uO200G9r9Vd1qGpeyJG87bZYhNvOsxLTw%2F1o3lze7z5U5Z33dfDyRsQxxd6pvBXz9RW7104DrmJ6IahuIAmEJzVTepWEElKzhcXsIaibPdzHAm4f7rOgLCDEUC8lxKCpCcRQ9xLxll5iayZK2BOBu5oo7KSs62GRKjhd%2FoWXEemhmywkDDfEOW%2FVcTJB9JyBrGWxRjFnKByBDI8zUtMFu%2BcEqRGTEk%2BRpPmVCevCSRb1TtN%2BDPRJEdCnVWHDoROQ6UMRzHqnH3sx0Xb08yBxn%2B7GSjKyHzlYiWxmpfLOlZMkkJYlEEJlDeorrAxXbD%2F%2FSZWmb%2FafSFgZBETMwK1pGZVZGciMZK5n7wkBHwFAUQ26DUgrjj7FXEcXgKLO0Q%2FdeDIMzFVxohlCsp4AgxHiZPl%2FvX4PRmSw%2Bkz%2Bv2P0uHzvI3r2rg1oDT00aPQgCz3LNNGh%2BDLEKtOyPJlOs0HSDbUEsszTHopAKOWBCaSpZ9kSv4ZOlBAYKsQaz3ZCygcb%2BvLOh661N11a08r8oR4ZZAWkO2ZPw0GIsR5XlzGRnkPl1bTqyYGeLXMc7aFHuKzpv57%2FfTj87diMggoxYCsHJ8I9Mzq04y1pYg9MSlCPnhkOTEaufN7%2BPExAfNMscVPcGTzXRsbkAGpsjSOwoSffbAptNj1iYJvER0Q1wUGMkFkSsy0KOOEb%2B%2FKNA%2BTi6wPa34Rxx2ZBWYWe4AALBImdfe%2BWrFEoKajTbLEx03NQOF%2BzvK5Uwa5txYTu6my3WaynMtKBEIo1echNx3pro8K40VPHpQpIQbN3rP5e6VKCUUvp0qynYNOlyM7OXZyHb4la20bSLJ7rOzmHfBSQH9M1erpGEzkT7WVrIrF6GZkbLgbC%2FrQzNbeLmS7ODytBAIVenchYWAkCZCdqr4aWfDrel%2BopbmtfKiiMBA1kwt5F2bnVmrcNixCyA%2FKz3sfc415gZSDd215g5RYxlSH%2F9LHvIfcJc%2BFaf4EcSy49jrkdIvzn86erzodd%2BIO6DDGzUFkwSsxNECCH%2FaPedrPffeheAB5xz%2FQUHYLEAfuOB932pc8uPltjvmGURw%2F3%2BUEgN9PnTDK1uwB2t7Om%2FGUDk9mBnTPD0LGxZtnY%2FnhHoWTNfq9MhDBUSwYaDZNVsqd1mQjpHVRTEdTId%2FiOUaJjIssHfHhr8OFhw8dlYm0LG2aA68colxFWKXrq2qWl2zg3cpwv9GLqAf3ISUAYoJx8rH870jFjpk42pWPZU8h0bNe7vJiJBU9sDPFJeFreczHwb6rlghFXur%2FMSGBrS5eWfHgB8ID2qPV9Vxv%2FnnDi3uC0wafvG07O8uODtiJcLXAqhY8c2c1ObQixU%2FpHj95U0f6ldMzOdeLP70HGGzz6nslYHc5x9OhXHr1xwFUAWt531K7qh06qtUPLyqHKvjXZUbHJbTIfzVraMBWHtZUDZOYBjiUMduUEBLGRv4XYOMHBu%2BL7WbqyM6ak4YBEwxUta9S23Vwk2tnOVMGnzkZ%2FeQXPRBhUBRrvT2pWOHCzJ%2B94tHMWH%2BPR5IWYokRePE1%2FbYLdLlPvxgop3nsVq%2BMguL8WcqCOIjJ1pj8R2d7cOlIvRr0tRl%2B743TWID9QAq2y%2BXI9jHEaHxO1pF6zF9ay%2Bc10pn6K%2FJ3FO3MrK7Vo5mvxbCRq7M1W5oO8VOtR7q1XLlowT3rb3noYizBXS3Ha3rfP1LlyF3uvG%2Fch6uN8g0bekii3py3hG9XAt7FCGu4VXR2VeVgaUh5VWWoIanjOmuVfCXOCsC0F4dT9oK11V4gNN1hP2HiDsR5HkA03UGP5nShKuj3r%2BHGaw8sOiIhAs7CRrJp2Dp2X3dXn07LjyHvMp1F7cuMIohZABNsFEQwaRMyOtA59hgwBZm7YA0nUd7zF7OmXQ58ky%2FyDAAW1W2B8pOUtaRkQWyv3oOVld%2BHS8gteVu9rYRw3d7MLQdn7Xm7%2Fmyq77MhaoaRWITZw48E6VWeC91no6uWk4iOEsgWE7UEIhg0hx%2BnCRyfe3H8HMgR6r5dm9tzj0Y3nJEhRHZN0nhx5WzMbE%2FOys3CJ2U7RHd1481TxIJSd23mwo7K34chHxqIlAaKGqi67WlvdykCfqs6P5dF%2B3Pj2AATDBpCdNzw68dRcBiFQ%2F6biJR9I48uFt1YxhCCoY3LOjwMfGVrZnJJlVyFTsmvXy4NWdCiMepkwFL3vBQaVg%2BE5qio6lIqO6hS9rLQ70fbJ3W6xi6Oorla%2B269%2FqRbOBVYhZ26UDqlZ%2BLl1hRw3V9fQrk%2Fy4MFsm6CbJdY%2B%2BLaoxQxs8RU1C39JY6Qx1BBpOxdjWl%2Ba0siAro9KRt53ktS5XpARnZU5IwYrI1bLyt1Sb7lvc8DUyymtbnFurARjGDs%2B3V1VzMJ%2BGq3r1ztD911dWZbhc8Qr4M6wW7eRvj%2FoBgZICq1aIJqVh4DVq%2Bk2%2FNb%2By9bRLm0xtnkwWfkkv4ytnto%2FsIUQGmtTznTaNli7KcLbPbWo3IE8YMLOKBnWErYAvA3CJtSqvuRwXc%2B%2BKVuEkoKHulNd8nWBaqjTOahbE%2Bidzje65iXWQwF2ZKUfKG5aAipd5nVujZDwtnWobSOAjHX1CBQ7%2F3g2An277ZXUKMAnum%2BON2ZMdG%2BfRqGYBnUeSMCmAUM2wBDgKOKIEW5OsDAUDYpPEKBcGJu9b3%2BaEQGDCGImimeZ5dVdH0Qt%2Bnbnm6IzVxLCjRgA1q3EbZf%2FFaBDQS8EYJDBkhKSQRVasIKDFebK6uyd0btJSbLzwFY6Qg0lacs2QDMiJsXZs%2FVaZ97Bir13vFoTDAIJKfoxC6HoBqBWGaWIxAAolEqVoQ31AZlpTCsj6pm%2FMejbt9%2BPv2mEdf5GLdB3MMATPPPiFFmqU8pXLgUa8BUp84YYzOCNyArMBtIRGHCbsVunZPPkaVGMl2eCRQ7001laAFV%2BMi5RTf9%2BTPLZXoXvShO9zf59rW6W3ya%2FP2%2B3NGrPo41iPObANTltaaJ2ZaX9ZvlqZ%2B6amJghjDmmrrlDU8wdNJpMXQ%2Bnyez1n%2BB29uEP%2FOHbn5df%2BPXFqXJg9qE1xTLLvY2QZgJRfvb32v3tBiQqS1FURqJ2csRBoZQOh%2FtNPu9wDDgKivmQkcEtpzB2JTcc6R15DI%2FcMGxhDVrgMAwEMhEmMnjLQpciTrGP%2BYVFbJNd0DD8RjJAwZUAhdpHFpPSVCLgLU%2FrBlsL1TpHsLUANh6BDsDGI9gn2FyFNprntEKdcpOyD04flu7KmbwA8vtn24e6Bts6UWHUB7bgQCEj%2Bc7UVOkGNKOoHrj7eU%2BuLHYrwoVH4VL7QPNuhevK2LYiXHTwwuUdau5%2F%2F3mD3n%2F%2B8ZSe0y%2FDy6u3JLpyxj3Di%2FeBCqASvaK2NvQF3AhGoRADjisvS0C%2BaqrdAvKzKwUB8c1W%2BTYjk1DeGbrLBaG5OEJ2PajUJalUzu75LzN9saHj9hyrx8un7%2BLx6ylZ3H3%2F3%2Fvv3%2BfRz4%2FuzMVu9IyIi56n8%2FvH9OAY2tptWO1c2gUDuAXsYoA2BJw8pkcJLzXa3z778u0iyUZ9pfLyZ91dJpM4u%2BL%2F)


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

