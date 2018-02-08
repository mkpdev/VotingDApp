Voting DApp

To setup:

Installing & Running the Ethereum TestRPC
The Ethereum TestRPC is a Node.js Ethereum client for the testing and developing smart contracts. Because it's based on Node.js, we need Node.js installed along with NPM (Node Package Manager) to install it.

> node -v
> npm -v

Instead of developing the app against the live blockchain, I used an in- memory blockchain (think of it as a blockchain simulator) called ganache

let's use NPM to install the ganache:
> npm install -g ganache-cli

Once finished, run the following command to start it:
> ganache-cli

This provides you with 10 different accounts and private keys, along with a local server at localhost:8545.

