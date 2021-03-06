# Ethereum-Dapp

A simple `Bank Transaction DAPP` with GUI.

***Solidity*** is the programming language used.

Metamask(Ropsten Test Network) is used for transaction fees(includes Amount+Gas fee ).

`bank.sol` is the file which contains your smart contract.

`index.html` file contains your GUI and Interaction part with the smart contract.

### Gas - Whenever we do a transaction , the miners want to get rewarded , so we have to pay them some fees known as Gas.

Ether is the cryptocurrency being used for transaction based on Ethereum.

Bootstrap is used for making GUI.


# Requirements

- Metamask Extension enabled on your browser.

- Account on Metamask.

- Get some free ether using any of the test network(prefer not to use Main Network as it may cost you some money for buying ether).

- Add Bootstrap CDN in your file to feel some great user experience.

- To make your Dapp run add the files given below:-
    

   - ###### *`https://code.jquery.com/jquery-3.3.1.slim.min.js`*

   - ###### *`https://cdn.jsdelivr.net/gh/ethereum/web3.js@1.0.0-beta.36/dist/web3.min.js`*
    
    
# Procedure to run it online

Visit [`Ethereum.org`](https://remix.ethereum.org/)

Select solidity on the main page as your programming language.

Write code there i.e given in `bank.sol` file to you.

Now compile and run it.

It will ask you for confirmation click confirm and then wait for a while.

In Deployed contracts you will see your contract address.

Along with this there is drop down menu by clicking on it you can interactively run your DAPP. 

# Procedure to run it offline

Clone or Download this repository.

Open your favouraite IDE(VSCode int my case).

Install npm to run it.

Use command `npm install http-server` to install http-server

To run type `http-server` in terminal/CommandPrompt and visit on the generated url or without installing anything just `open live server` in VSCode that will make it run directly.

You can use your own abi and address by visiting online IDE that we are previously using.


# Make Your Own Code

If you want to make your own Dapp then copy/write code which is written in `bank.sol` in the online ide [`Ethereum.org`](https://remix.ethereum.org/), compile it and then just only replace your `abi` and `address` with mine in `index.html`. You will find `abi` at the solidity compiler option(on left of ide) and `address` at deploy&run transaction option(on left of ide as well).

Copy these things and replace it with mine.

There you Go !!!

#
![alt text](https://github.com/VersatileVishal/Ethereum-Dapp/blob/master/Ethereum.png)
