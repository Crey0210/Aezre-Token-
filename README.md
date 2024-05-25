# Aezre Token
Aezre Token, "AZR", is an ERC20 token created and deployed in remix ide. Just like any other token, it has several functions such as minting a token which is only callable by the owner, transfer token from one account to another, and burn token from the caller's account.

# Description
This program is a simple contract written in Remix Ethereum, a programming language used for developing smart contracts using OpenZepplin, a give-and-take website that gives you free Codes for Tokens and in doing so takes a lot of people to their cause. These are a few codes in that can work perfectly in your favor as OpenZepplin gives you a GitHub that automatically gives you your initial code without even typing it. Just give a little more minting and coding and it's done very easily.

## Getting Started
Firstly, you have to set up what you need, the applications and GitHub;
Open the website OpenZepplin and find a GitHub of your choice, it's pretty easy and only open it within your tab for further use. 
Next is remix Ethereum, if you have this, you're good to go!

### Coding
First off, go to remix Ethereum and create a file called "token.sol" (sol is important as it is the .sol that differs from other code) put these commands first
You are free to change whatever name you want to name your file. But I recommend just name it teh name of your token,
```
// SPDX-License-Identifier: UNLICENSEDS
//SPDX-Lisence-Identifier: MIT
pragma solidity ^0.8.20;
import "github of openzepplin";

```
Pragma Solidity is the one you need to see, you can change the version if you go to the "Solidity compiler" to check if you're up to date or if you want to change the compiler. 
importing the GitHub is the first and foremost of what you need to do, then run it so it'll read  the GitHub itself.

```
contract AezreToken is ERC20("AezreToken", "AZR"){

    [Your functions are written here]
    }
    
}
```
Contract (the name of your token) is ERC20. ERC20 is the important one in this code here as it is to call the contract inside the OpenZepplin


## Running the code
Once you are all done there you can compile it in the Solidity Compiler on the left side. Make sure the pragma solidity version in your contract is the same to the compiler version. Of you go to deploy and run, copy your address, and deploy your code. If you deployed it you need to scroll down and go to "deployed contracts". You'll have 100 ethers from the Remix VM Environment that you chose. Then you can now interact with it. Just make sure you have enough gas for all the transactions

# Authors
Cyrus John N. Reynoso/ 3.1BIST/ NTC

# License
This project is licensed under the MIT License - see the LICENSE.md file for details
