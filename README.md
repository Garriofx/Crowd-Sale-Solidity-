# Crowd-Sale-Solidity

![image](https://user-images.githubusercontent.com/81495204/132804035-141fb278-4b26-408e-90d6-60b8b656313f.png)

New startup has decided to crowdsale their PupperCoin token in order to help fund the network development. This network will be used to track the dog breeding activity across the globe in a decentralized way, and allow humans to track the genetic trail of their pets. Necessary legal bodies have been contacted and they have given the green light on creating a crowdsale open to the public. However, company is required to enable refunds if the crowdsale is successful and the goal is met, and it is only allowed to raise a maximum of 300 Ether. The crowdsale will run for 24 weeks.

ERC20 token should be created and will be minted through a Crowdsale contract that can leverage from the OpenZeppelin Solidity library.

This crowdsale contract will manage the entire process, allowing users to send ETH and get back PUP (PupperCoin). This contract will mint the tokens automatically and distribute them to buyers in one transaction.

It will need to inherit Crowdsale, CappedCrowdsale, TimedCrowdsale, RefundableCrowdsale, and MintedCrowdsale.

Crowdsale will be executed via Kovan Testnet in order to get a real-world pre-production testing.
