# About
The whitelist contract is a smart contract written in Solidity that allows for the creation and management of a whitelist of addresses. It includes a variable called `maxWhitelistedAddresses` which represents the maximum number of addresses that can be whitelisted. The contract provides a function called `addAddressToWhitelist` which allows the anyone to add addresses to the whitelist if the `maxWhitelistedAddresses` limit is not reached.

# initializations
```bash
npm init --yes
npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox
npx hardhat
npm install dotenv

```

# Deploy your Contract

To deploy your contract, type the following in your Terminal:
```bash
npx hardhat run scripts/deploy.js --network sepolia
```

# contract deployment information 
Whitelist Contract Address: 0xD98eA6f55AE77bdE11556A9BE77647C5DCA16200

The contract 0xD98eA6f55AE77bdE11556A9BE77647C5DCA16200 has already been verified.

https://sepolia.etherscan.io/address/0xD98eA6f55AE77bdE11556A9BE77647C5DCA16200#code


