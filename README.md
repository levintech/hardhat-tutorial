# Simple Hardhat scripts

1. Installation and init an (empty) sample project
2. Write ERC20 token with OpenZeppelin
3. Write ERC721 NFT token with SVG iamge on-chain

 
## Installation and init an (empty) sample project
- Make sure Node and hardhat are installed on your pc
- Init Hardhat project
  `yarn hardhat`
- Set configuration (hardhat.config.js)
- Compile, Test and Deploy
  `yarn hardhat compile`
  `yarn hardhat test`
  `yarn hardhat run scripts/sample-script.js`

## Write ERC20 token with OpenZeppelin
- Contract ("Gold", "GLD")
    `GLDToken.sol`
- GLDToken-deploy.js
    `yarn hardhat run scripts/GLDToken-deploy.js`
- GLDToken-test.js
    `yarn hardhat test test/GLDToken-test.js`
## Write ERC721 NFT token with SVG image on-chain
- Contract
    `BadgeToken.sol`
- BadgeToken.js
    `yarn hardhat run scripts/BadgeToken.js`
- BadgeToken-test.js
    `yarn hardhat test test/BadgeToken-test.js`
