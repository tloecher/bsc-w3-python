# Interacting with Binance Smart Chain (web3/Python)

Recently Pancake Swap forks have been popping up at an alarming rate in the BSC ecosystem.  
Some of these yield farm launches were quite hotly anticipated by the community.  
And the team over at Goose Finance decided to limited pool size to increase APY (and up the general FOMO).

So you had to be fast. 
Faster than browser based clicking and metamask would allow.

So I decided to write a script to do the following things:
- Fetch the available pool size
- Approve the pool's contract
- Deposit funds into the pool  

In order to do that I needed the following:
- An API to access BSC => Ankr
- A couple of ABIs for the tokens and pool contracts => BSCScan
- And crucially the new pool's contract address => camping BSCScan

Execution time (including human interaction): sub 30 seconds
