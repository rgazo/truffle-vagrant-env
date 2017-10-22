Truffle (Ethereum) dev vagrant box
===

* Contains Solc compiler, Ethereum, testrpc, Truffle

Setup
---

* Create a *DAPPS* folder in *~* (it will be synced to */home/vagrant/DAPPS*)

* Start the vagrant box and log in
```
> vagrant up
> vagrant ssh
```

* Crate your first DApp
```
> cd DAPPS
> mkdir first
> cd first
> truffle init
```

This will create a test project using Truffle framework with some demo contracts (check out the newly created folders).

In a separate window log in to vagrant
```
> vagrant ssh
```

Start testrpc
```
> textrpc
```

Here you will see what your contracts ar doing.

You can deploy the truffle demo (MetaCoin) or delete the demo and create your own contracts.
To deploy:
```
> truffle deploy
```

Switch to the testrpc window to see what is happening on the Ethereum test client.

Read
---

* [What is Blockchain Technology? A Step-by-Step Guide For Beginners](https://blockgeeks.com/guides/what-is-blockchain-technology/)
* [Ethereum White Paper](https://github.com/ethereum/wiki/wiki/White-Paper)

* [A 101 Noob Intro to Programming Smart Contracts on Ethereum](https://medium.com/@ConsenSys/a-101-noob-intro-to-programming-smart-contracts-on-ethereum-695d15c1dab4)
* [Hello World!](https://ethereum.org/greeter)

* [Solidity Documentation](https://solidity.readthedocs.io/en/latest/)
* [web3.js - Ethereum JavaScript API](https://web3js.readthedocs.io/en/1.0/)
* [Truffle](http://truffleframework.com/)
* [testrpc - a Node.js based Ethereum client for testing and development](https://github.com/ethereumjs/testrpc)
