# Token Creation - Solidity

Token Creation, Minting and Burning using [Solidity](https://en.wikipedia.org/wiki/Solidity#:~:text=Solidity%20is%20an%20object%2Doriented,0.) Programming Language.

## Description

This program uses Solidity and allows the user to do the following functions:
* Creation - Creating META Token
* Minting - Minting certain number of tokens in the provided address
* Burning - Burning certain number of tokens from the provided address
* Finding balance - Finding out the META Token balance of the given address
* Finding Total Supply - Finding total supply of the META token

## Getting Started

### Installing

 Import this repo into [Remix IDE](https://remix.ethereum.org/). Here is a [short video](https://www.youtube.com/watch?v=vExMiQZpHpQ) on how to do this.

### Executing program

* After importing the repo, in the Remix IDE, open then the contracts folder and then click on tokenFunctions.sol file
* Then click on 'Solidity Compiler' icon present on the left vertical panel and then click on 'Compile tokenFunctions.sol' button
* Then click on 'Deploy and Run Transaction' icon present right below the Solidity Compiler icon 
* Click 'Deploy' button
* Expand the Deployed contract section
* Enter an address and the number of tokens to be minted in the 'mint' section and click 'transact' button
* Similarly, 'burn' function can also be used to burn some tokens 
* Using 'balances' button, we can find out the balance of the provided address
* Using 'tokenSupply' button, we can figure out the Total Supply of the META token available
* Using 'tokenName' and 'tokenAbbrv' buttons, we can see the Name of the token and its abbreviation respectively