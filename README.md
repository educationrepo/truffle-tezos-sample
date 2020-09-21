# truffle-tezos-sample

clone the repo
cd truffle-tezos-sample-repo
truffle compile

take another terminal
 npm run start-sandbox
 truffle migrate

Interacting with smart contract through truffle console

truffle console
truffle(development)> let instance = await Counter.deployed()
truffle(development)> await instance.increment(2) 
