# Erc721a-Solidity-Contract by ReservedSnow

## features:
* Gas efficent 
* Uses new erc721a standard
* Uses merkle tree for low gas and offchain wl
* Has functions to change many parms later on after deploying 

## Make sure your compiler settings are:
* v0.8.9
* enable optimization: 200
* Follow the comments to change the settings as per your needs 

## Some things to keep in mind:
* Flatten the contract before you deploy.
* Use a dummy CID for prefix , change it later using a write function when you want to reveal.
* Copy the bytecode after you enter the value in constructor.
* copy the abi in order to use the contract with a dapp and to parse it later to bytecode if you forgot to copy the bytecode.
* set roothash with setroothash function.

## Please fully test it on testnet before using for production/ on mainnet
   please review this code on your own before using any of
   the following code for production.
   ReservedSnow will not be liable in any way if for the use 
   of the code. That being said, the code has been tested 
   to the best of the developers' knowledge to work as intended.
   If you find any problems please let the dev know in order to improve
   the contract and fix vulnerabilities if there is one.

## Support the dev 

https://crypto-to.me/ReservedSnow
