# Interacting with Binance Smart Chain using web3/Python

Due to the persistently high gas prices on ETH volume has shifted across to Binance Smart Chain (BSC). 
As a result of this increased attention a large number of Pancake Swap forks have popped up. 
The launch of new projects followed a predictable pattern of sky high APYs which quickly plummeted as yield farmers piled in.  

So the team over at Goose Finance decided to limited pool size in their layered farms to increase APY (and inadverently FOMO). 
It's undoubtedly true that layered farming was little more than a pyramid scheme in fancy dress. 
But at double digit daily yields it seemed to offer reasonable rewards for the risk taken.  

But you had to be fast because everyone wanted to get in. 
Faster than clicking buttons in your browser and metamask.  

So I decided to write a script to do the following things:
- Fetch the available pool size
- Approve the pool's contract
- Deposit funds into the pool  

In order to do that I needed the following:
- An API to access BSC => Ankr
- A couple of ABIs for the tokens and pool contracts => BSCScan
- And crucially the new pool's contract address => camping BSCScan

The resulting execution time (including some human interaction): sub 30 seconds.  
