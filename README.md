# Random Raffle Contracts

## About

This code is to create proveably smart contract lottery

## What we want it to do

1. Users can enter the lottery by paying for a ticket
   1. The ticket fees are going to go to the winner during the draw
2. After X amount of time the lottery will automatically draw a winner
   1. And this will be done programatically
3. Using Chainlink VRF and Chainlink Automation
   1. Chainlink VRF->Randomness
   2. Chainlink Automation->Time based trigger

## Tests

1. Write some deploy scripts
2. Write our tests
   1. Work on a local chain
   2. Forked testnet
   3. Forked Mainnet
