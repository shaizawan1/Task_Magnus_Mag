# Blockchain Developer Exercise
first of all we select the vm london and the click the deploy button the smart contract will be deployed 
the following fucntions will appears.

![image](https://user-images.githubusercontent.com/92707096/175656355-f2b15884-394c-4403-a906-4b1d62d9f391.png)

here sendAmount will be use to send ethers or Weis to our smart contract. we simply select the address and enter the value of crypto(ether or wie) then hit sendAmount.
as we hit sendAmout we will see the log file first the amount has be deposited to our smart contract then it will go to deployer address as the log image shown below.

![image](https://user-images.githubusercontent.com/92707096/175656760-35084e21-d9a7-44a7-be7f-98da3f52dc75.png)

Now we can see the log file what happen with this single click!


status	true Transaction mined and execution succeed
transaction hash	0xa05930ff2e891b73db904e486f82d328138d4d69fe5befa58d50387f6159e27b
from	0xAb8483F64d9C6d1EcF9b849Ae677dD3315835cb2
to	Task.sendAmount() 0x93f8dddd876c7dBE3323723500e83E202A7C96CC
gas	49275 gas
transaction cost	42847 gas 
execution cost	42847 gas 
input	0x8b2...b3d8b
decoded input	{}
decoded output	{}
logs	[
	{
		"from": "0x93f8dddd876c7dBE3323723500e83E202A7C96CC",
		"topic": "0x8063d293b181cf972b260080914377cc16492b64b4c25192855b848abc3f3010",
		"event": "balanceDetials",
		"args": {
			"0": "The contract Got:  ",
			"1": "10000000000000000000",
			"message": "The contract Got:  ",
			"blnc": "10000000000000000000"
		}
	},
	{
		"from": "0x93f8dddd876c7dBE3323723500e83E202A7C96CC",
		"topic": "0x8063d293b181cf972b260080914377cc16492b64b4c25192855b848abc3f3010",
		"event": "balanceDetials",
		"args": {
			"0": "Before getting balance the deployer have: ",
			"1": "98999999999997221787",
			"message": "Before getting balance the deployer have: ",
			"blnc": "98999999999997221787"
		}
	},
	{
		"from": "0x93f8dddd876c7dBE3323723500e83E202A7C96CC",
		"topic": "0x8063d293b181cf972b260080914377cc16492b64b4c25192855b848abc3f3010",
		"event": "balanceDetials",
		"args": {
			"0": "after sending amount to deployer the contract will have: ",
			"1": "0",
			"message": "after sending amount to deployer the contract will have: ",
			"blnc": "0"
		}
	},
	{
		"from": "0x93f8dddd876c7dBE3323723500e83E202A7C96CC",
		"topic": "0x8063d293b181cf972b260080914377cc16492b64b4c25192855b848abc3f3010",
		"event": "balanceDetials",
		"args": {
			"0": "After getting balance by the deployer have: ",
			"1": "108999999999997221787",
			"message": "After getting balance by the deployer have: ",
			"blnc": "108999999999997221787"
		}
	}
]
