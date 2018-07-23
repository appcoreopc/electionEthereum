# electionEthereum

Repository for Election Contract

Go to Remix (https://remix.ethereum.org) and paste Election.sol into the editor. Compile. We will run this later. First we need to setup your account and get some ether! 


Install Metamask. 

Select "Ropsten Test Network". Create an account and then copy the account to clipboard.

Get your ether by http://faucet.ropsten.be:3001/ and then under "Enter our testnet account address", enter our test account address and click "Send me 1 test ether". Normally you can't send yourself more than 1 ether under 1 min. Please wait awhile before you can get more test ether. 

Go and check your account. It should have some mone in there.

Now lets deploy the contract, select "Run" tab and under environment, select "Injected Web3 - Ropsten". When you click "Deploy", Metamask will show up and you need to make sure you enter gas price (wei) > 1. When you click Submit, your concract gets deployed. 


Goto Etherscan (https://ropsten.etherscan.io) and see that we have some transaction history. 


Look at the contract you have just deployed. Red means pay. Blue means free

How to work with your contract. 

1. To see candidate, enter 1 at the "candidates" and noticed that it returns "Jeremy". 

2. To vote, you need to fill up, candidates and vote. For example 

  Candidates : 1  (Jeremy) 
  Vote :       1  (I get a vote)
  
  When you click on Vote, Metamask pops ups again. Click "Submit" to confirm vote. 
  
  
  You will noticed transaction history appears in Metamask. 
  
  You can also go here (https://ropsten.etherscan.io/) to see transaction history.
  
  
  
  
  
  
  
  
  
