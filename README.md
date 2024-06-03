# Metacrafters_6
Eth proof(intermediate)- Create a unique token of the ERC20 type that can be earned by the players in the game and then exchanged for their rewards in their in-game store.

# Description

ERC-20 contracts are named for standard functional tokens so that they behave just like Ether (ETH). We link our metamask wallet to the remix IDE by changing the environment to Injected Provided- MetaMask. In the metamask wallet we change the network from the Etherium main to the Avalanche Testnet, since our balance is zero AVAX in the account, we cannot deploy our contract as it needs some gas cost to deploy. In order to add free Avax we use the Core beta software, under this, we use Avalanche Testnet Faucet. Once we add the address the Avax will be credited. To keep track of the transactions done or the activity we use Snowtrace testnet software. In the contract, we import the required modules and declare some functions for minting new tokens, transferring tokens, redeeming tokens, checking token balances, burning tokens, etc. These are used by the players to earn, transfer and redeem their tokens.


# Getting started

The DegenToken contract is an ERC20 token smart contract that enables various functionalities for players in the Degen Gaming platform. The contract is designed to provide the following features:

1) mint  - the function allows the contract owner to create new tokens and distribute them to the players accordingly by mentioning their addresses.
   
2) transfertokens  - players can transfer their tokens to others, they can initiate the transfers by mentioning the recipient's address and the number of tokens to be transferred.

3) checkbalance  - it allows players to check their token balance present in their account or wallet.

4) burntokens  - the player can burn his/her tokens if they are no longer needed or for any purchase in the game store by mentioning the number of tokens to be burned.

5) gamestore  - it shows the available items in the game store so that players can choose their respective game and redeem their tokens.

   

# Video walkthrough

https://www.loom.com/share/f4f9c8760b984792aa160264534edd1d?sid=cc24d154-a836-4f93-a3cb-5fe6bda564ab


# Authors

BYLAPUDI DEEPAK VENKATA SWAMY NAIDU @bdvsnaidu(https://github.com/bdvsnaidu)
