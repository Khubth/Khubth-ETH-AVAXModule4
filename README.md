# Khubth-ETH-AVAXModule4

## DegenToken
DegenToken is an ERC20 token deployed on the Avalanche network for Degen Gaming. This smart contract allows the owner to mint new tokens, and players to transfer, redeem, and burn tokens. Players can also check their token balances at any time.

# Features
## Minting New Tokens:
* The platform owner can mint new tokens and distribute them to players as rewards.
## Transferring Tokens: 
* Players can transfer their tokens to others.
## Redeeming Tokens: 
* Players can redeem their tokens for items in the in-game store.
## Checking Token Balance: 
* Players can check their token balance at any time.
## Burning Tokens: 
* Players can burn tokens that they own and no longer need.

# Deployment
* To deploy this contract on the Avalanche network using Remix IDE and MetaMask, follow these steps:

1 Open Remix IDE: Go to Remix IDE.

2.Load Contract Code: Copy the smart contract code and paste it into a new file in Remix IDE.

3. Compile the Contract:
* Click on the "Solidity Compiler" tab.
* Select the appropriate Solidity version (0.8.20).
* Click "Compile DegenToken.sol".

4. Deploy the Contract:
* Click on the "Deploy & Run Transactions" tab.
* Select "Injected Web3" as the environment to connect to MetaMask.
* Ensure your MetaMask is connected to the Avalanche network.
* Select the DegenToken contract from the dropdown.
* Click "Deploy".
* Confirm the transaction in MetaMask.

5. Interact with the Contract:
* After deployment, you can interact with the contract using the Remix interface.
* Use the available functions to mint, transfer, redeem, check balance, and burn tokens.

6. Check Transactions on Snowtrace Testnet:
* Go to Snowtrace Testnet.
* Copy the address of your deployed contract from Remix IDE.
* Paste the address in the Snowtrace testnet search bar to view the transaction history.

# Usage
1.Mint Tokens: Only the owner can call the mint function to create new tokens.
2.Transfer Tokens: Use the transfer function to send tokens to another address.
3.Redeem Tokens: Call the redeem function to exchange tokens for in-game items.
4.Check Balance: Use the balanceOf function to view your token balance.
5.Burn Tokens: Call the burn function to destroy unwanted tokens.

# Events
ItemRedeemed: This event is emitted when a player redeems tokens for an item.

# Author
Khushi Ranjana
21BCS9320
