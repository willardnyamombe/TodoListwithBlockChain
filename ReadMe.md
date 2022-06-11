## ETh-todoApp
Creating a todo using blockchain
# Steps
- make sure you have installed node on computer 
- insstall metamask and enable the extension on googlechrome
- download and install truffle from here:
 [ganache download](https://trufflesuite.com/ganache/)
 - run ```npm install -g truffle@5.0.2``` on your terminal
- Navigate to a folder for your project from the terminal
- Once inside the folder check the truffle version by typing ```truffle version``` you should see:
```
Truffle v5.0.2 (core: 5.0.2)
Solidity v0.5.0 (solc-js)
Node v17.3.0
```
- Initialize the project by typing``` truffle init``` and run.
- create a file and name it package.json like this ```touch package.json```
- then copy this code [package.json](https://github.com/dappuniversity/eth-todo-list/blob/master/package.json) and paste it inside the package.json file
- then use the editer of your choice
- on terminal npm install
- inside the contracts folder create a TodoList.sol file
- indide TodoList file add: 
```
pragma solidity ^0.5.0;

contract TodoList {
    uint public taskCount = 0;
}
```
- then on terminal run ```truffle compile```

*** from here you can follow this tutorial [YouTube tutorial](https://www.youtube.com/watch?v=coQ5dg8wM2o&t=630s)