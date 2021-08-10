# Gitcoin: 7) Use Force Bridge to Deposit Tokens From Ethereum to Polyjuice

## 1. Screenshots or video of your application running on Godwoken.


![](1.png)
![](2.png)
![](3.png)
![](4.png)

## 2. Link to the GitHub repository with your application which has been ported to Godwoken. This must be a different application than the one covered in this guide.

eg: 

input 1, show 1000

input 1234, show 1234000

.....

https://github.com/Dex68/nervos_gitcoin/tree/main/task7/Multiplied_by_1000
   

## 3. If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)

<b>Deployed contract address: 0x9E0824D01A3D8B2128b868bca7962fCEf61eB1Aa
</b> <br><br>

  <b>Deploy transaction hash: 0x1f41183a79cfe3dc17515ead17de543090eaf15cce555f6633a4371ce14d6f1c
</b> <br><br>

```
"abi":[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]


```
