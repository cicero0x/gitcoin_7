# Gitcoin Task 7

# Screenshots of application running on Godwoken
The application is a fork of an ethereum todo-list by Dapp University. The user is able to add and remove items by signing a transaction.
The github link to the fork can be found <a href="https://github.com/hodlrtodlrfarmr/todolist-fork"> here</a>. 

<img src="https://github.com/hodlrtodlrfarmr/gitcoin_7/blob/main/showcase.png">
<img src="https://github.com/hodlrtodlrfarmr/gitcoin_7/blob/main/showcase2.png">
<img src="https://github.com/hodlrtodlrfarmr/gitcoin_7/blob/main/showcase3.png">
<img src="https://github.com/hodlrtodlrfarmr/gitcoin_7/blob/main/showcase4.png">
<img src="https://github.com/hodlrtodlrfarmr/gitcoin_7/blob/main/showcase5.png">


# Transaction hash of the deployment transaction (in text format)
```sh
0xb4541f448378c7a271a5019653742c460989d849c94a21a5d04bbb2cd71c6630
```

# Deployed contract address (in text format)
```sh
0xF4087b1f7c58805EC9D26F3291a9A57Af9A0E065
```

# ABI of the deployed smart contract (in text format)
```sh
[
    {
      "constant": true,
      "inputs": [
        {
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "tasks",
      "outputs": [
        {
          "name": "id",
          "type": "uint256"
        },
        {
          "name": "content",
          "type": "string"
        },
        {
          "name": "completed",
          "type": "bool"
        }
      ],
      "payable": false,
      "stateMutability": "view",
      "type": "function",
      "signature": "0x8d977672"
    },
    {
      "constant": true,
      "inputs": [],
      "name": "taskCount",
      "outputs": [
        {
          "name": "",
          "type": "uint256"
        }
      ],
      "payable": false,
      "stateMutability": "view",
      "type": "function",
      "signature": "0xb6cb58a5"
    },
    {
      "inputs": [],
      "payable": false,
      "stateMutability": "nonpayable",
      "type": "constructor",
      "signature": "constructor"
    },
    {
      "anonymous": false,
      "inputs": [
        {
          "indexed": false,
          "name": "id",
          "type": "uint256"
        },
        {
          "indexed": false,
          "name": "content",
          "type": "string"
        },
        {
          "indexed": false,
          "name": "completed",
          "type": "bool"
        }
      ],
      "name": "TaskCreated",
      "type": "event",
      "signature": "0x05d0fb833127fc08168556d0e7ca9554fc3f6bc843b3b7d2bf1c35aea6bab660"
    },
    {
      "anonymous": false,
      "inputs": [
        {
          "indexed": false,
          "name": "id",
          "type": "uint256"
        },
        {
          "indexed": false,
          "name": "completed",
          "type": "bool"
        }
      ],
      "name": "TaskCompleted",
      "type": "event",
      "signature": "0xe21fa966ca5cd02748c0752352d18c48165e61cb55b4c29cccf924b5a95fcff1"
    },
    {
      "constant": false,
      "inputs": [
        {
          "name": "_content",
          "type": "string"
        }
      ],
      "name": "createTask",
      "outputs": [],
      "payable": false,
      "stateMutability": "nonpayable",
      "type": "function",
      "signature": "0x111002aa"
    },
    {
      "constant": false,
      "inputs": [
        {
          "name": "_id",
          "type": "uint256"
        }
      ],
      "name": "toggleCompleted",
      "outputs": [],
      "payable": false,
      "stateMutability": "nonpayable",
      "type": "function",
      "signature": "0x455f5024"
    }
  ]
