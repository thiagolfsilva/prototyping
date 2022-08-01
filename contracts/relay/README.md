### Relay Contract

Parameters: {'sender', 'receiver', 'amount', 'token_address'}

How to use it:

1. The 'sender' approves the address of the contract to spend the token at 'token_address'.

2. The 'sender' calls the send_token() function, the function will transfer 'amount' of token from the sender address to the contract address. Only the sender can call this function.

3. The 'receiver' can call the 'receive_token' function, and the contract will transfer 'amount' of token from the contract address to the receiver. Only the receiver can call this function.

Contract deployed for testing at: https://ropsten.etherscan.io/address/0xc7f7f967ed19cc45ca62997a6ccac3a09337580e