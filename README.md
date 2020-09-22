# truffle-tezos-sample

## clone the repo

> cd truffle-tezos-sample-repo
- then run the command in terminal
> truffle compile

- take another terminal:

 > npm run start-sandbox
 > truffle migrate

## Interacting with smart contract through truffle console

>truffle console
- create instance
>truffle(development)> let instance = await Counter.deployed()
- interact with smart contract function
>truffle(development)> await instance.increment(2) 
