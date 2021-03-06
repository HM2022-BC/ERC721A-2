# What is ERC721A-2?

Based on the new standard of Azuki ([ERC721A](https://etherscan.io/address/0xed5af388653567af2f388e6224dc7c4b3241c544)), we try to push the gas prices further through less flexibility to offer a cheaper mint (due to lower gas fees). In addition, we are adding the possibility to give users a spot on a whitelist, which can purchase their NFT at an earlier time slot (e.g. 5 hours before the actual Mint) without the need to hurry.

# Setup dependencies 

```
npm i
```

create an .env file

```
export PRIVATE_KEY=[METAMASK_PRIVATE_KEY]
export WEB3_INFURA_PROJECT_ID=[PROJECT_ID]
export ETHERSCAN_TOKEN=[ETHERSCAN_API_TOKEN]
export REPORT_GAS=true
```

# Compile
```
npx hardhat compile
```

# Run script
run remote

```
npx hardhat run scripts/create_collectible.js --network [NETWORK_NAME]
```

or local

```
npx hardhat run scripts/create_collectible.js
```

# Report gas use

```
npx hardhat test
```