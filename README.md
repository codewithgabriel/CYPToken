# ERC20 sample project

CYPToken is a ER20 (demo) token it is build with hardhat framework, you can use this as a start up for your ERC20 token project


Try running some of the following tasks:

Getting Started

1. First create account on alchemy
2. create new app on alchemy (choose mumbai polygon test net)
3. copy the https end point url
4. generate your wallet private key, I recommend metamusk
5. edit hardhat.config.js in the project dir
6. set networks 


```shell
networks : { 
mumbai : { 
		url: your_alchemy_endpoint_url ,
		account: your_wallet_account_private_key
	}
}
```


```shell
npm install # To install dependencies
npx hardhat # To compile the solidity code
npx hardhat # To run the test.js script under the test folder

Usefull commands to try

npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

# CYPToken
