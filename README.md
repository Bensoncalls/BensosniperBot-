# BensosniperBot-
The aim of BSC Token Sniper is to buy new tokens with a specified amount of BNB, with the aim of the price rising Once the bot detects a PairCreated event, it is able to check the token (mini audit). It can check if:  Source code is verified. If valid PancakeSwap v2 router is being used If a mint function exists If it is a potential honeypot PancakeSwap v1 router address is not being used. The user can decide whether to enable the mini audit or turn it off (bear in mind you will likely be investing in a lot of scams if you don’t). Once the token has/hasn't been through a mini audit the bot will then attempt to buy X amount of tokens with the specified amount of BNB. The bot will buy the tokens directly through the Binance Smart Chain using the PancakeSwap v2 router and factory address, so it is much quicker than the PancakeSwap web interface. By avoiding web interfaces &amp; Metamask and directly with Ethereum &amp; EVM Nodes you can snipe tokens faster than any of the web-based platforms. This allows tokens to be sniped almost instantly. During our testing we found the bot would typically be within the first 3 buy transactions of all tokens it finds. The bot buys the tokens using the user's wallet address and private key. This information is kept secure, is only stored locally on your computer, and is only ever used to buy tokens (look through the code to see for yourself). The bot does not incur any additional fees, only fees are BSC network transaction fees and PancakeSwap fees.
