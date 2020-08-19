# Solidity_Crowdsale

Using Remix, I designed an ERC20 coin called "PupperCoin." I used the standard ERC20Mintable and ERC20Detailed contract to created the ERC20 Puppercoin.

After creating the ERC20 coin, I launched a hypothetical crowdsale of the PupperCoin token to fund the network development. 

The crowdsale is allowed to raise a maximum of 300 Ether and will run for 24 weeks. The crowdsale contract will manage the entire process, allowing users to to send ETH and get PupperCoin back. 

The contract also mints the tokens automatically and distributes them to buyers in one transaction. 

In order to accomplish all of this, I inherited Crowdsale, CappedCrowdsale, TimedCrowdsale, RefundableCrowdsale, and MintedCrowdsale from OpenZeppelin. 

Lastly, the crowdsale is conducted on the Kovan or Ropsten testnet in order to get a real-world pre-production test in.
