# Staking-With-ERC4626

*en* 
Staking and receive rewards, Rewrite ERC4626 implementation to add logic for reward calculation.<br> 

*zh* 
继承ERC4626"代币化金库标准"的实现：*https://eips.ethereum.org/EIPS/eip-4626[EIP-4626]*,
并在ERC4626金库标准上增加奖励的相关逻辑.

### Standard
ERC-4626: Tokenized Vaults with a single underlying EIP-20 token.


### How to deploy
Prepare your env file，Then execute the following command：

`
npx hardhat --network localhost run .\scripts\deploy.js 
`