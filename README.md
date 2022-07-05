# ERC721A-2

create an .env file

`export PRIVATE_KEY=[METAMASK_PRIVATE_KEY] \n export WEB3_INFURA_PROJECT_ID=[PROJECT_ID] \n export ETHERSCAN_TOKEN=[ETHERSCAN_API_TOKEN] \n export REPORT_GAS=true`

# compile
npx hardhat compile

# runscript
run remote

`npx hardhat run scripts/create_collectible.js --network ropsten`

or local

`npx hardhat run scripts/create_collectible.js`

# report gas use

npx hardhat test