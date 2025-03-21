# Technical review challenge

## Problem 

One of the ways how Monerium makes money is via interest earned on custodied euros. 
We would like to know who are the top 10 addresses who have earned the most interest for Monerium
since 2022. 

## Objective 

Build a solution that can 
- Fetch the EURe balance changes for all addresses 
- Calculate the interest earned for each address 
- Return the top 10 addresses who have earned the most interest for Monerium since 2022
- For the interest calculation you can use an average of 3% per year.
- Include addresses from 3 chains: Ethereum, Polygon, Gnosis

This solution should serve as a foundation to build additional features on top of it. Think real
time balance monitoring, alerting system when EURe is transferred to a specific address, etc.

## Resources 

- You can find the token info and addresses at https://monerium.dev/docs/tokens 
- You can find public rpc endpoints on https://chainlist.org/
- We upgraded the tokens on Gnosis, Polygon, Ethereum. You need to fetch V1 events up to a specific block height, then switch to V2. You can read more about that here: https://monerium.dev/docs/contracts-v2
- Example transaction data for EURe https://etherscan.io/token/0x39b8B6385416f4cA36a20319F70D28621895279D 
- Example transfer event log: https://etherscan.io/tx/0xc51215800f6a0f05618e7289135da2d008a48177faff4b5497fd189671762d83#eventlog

