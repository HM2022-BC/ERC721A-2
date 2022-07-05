# What is ERC721A-2?

Based on the new standard of Azuki ([ERC721A](https://github.com/chiru-labs/ERC721A)), we try to push the gas prices further through less flexibility to offer a cheaper mint (due to lower gas fees). In addition, we are adding the possibility to give users a spot on a whitelist, which can purchase their NFT at an earlier time slot (e.g. 5 hours before the actual Mint) without the need to hurry.

# ERC721A-2

create an .env file

```
export PRIVATE_KEY=[METAMASK_PRIVATE_KEY]
export WEB3_INFURA_PROJECT_ID=[PROJECT_ID]
export ETHERSCAN_TOKEN=[ETHERSCAN_API_TOKEN]
export REPORT_GAS=true
```

# compile
```
npx hardhat compile
```

# runscript
run remote

```
npx hardhat run scripts/create_collectible.js --network ropsten
```

or local

```
npx hardhat run scripts/create_collectible.js
```

# report gas use

```
npx hardhat test
```