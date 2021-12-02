# NoWayHomeToken
This is a solidity ERC20 token contract whose main aim is to prevent rapid pump and dump. This is done by preventing the investors to swap the token back to bnb or eth for a specific period of time (according to this contract for a period of 1 week) before allowing swap on DEX.

This contract focused on the pancakeswap DEX on the testnet of the bsc network. 
It target the swapExactEthtoTokens function in the IPancakeswapRouter contract class to manipulate the time the withdrawal will be allowed.
