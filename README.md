# Supply chain & data auditing

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

## UML diagrams
[Activity diagram](uml/activity.png)
[Data modelling](uml/Data-modelling.png)
[Sequence diagram](uml/sequence.png)
[State diagram](uml/state-diagram.png)


## Contracts created in Rinkeby test network
  'FarmerRole'
   ----------------------
   > transaction hash:    0xb65533ffe85eba1ec8e2c7a49a0e582ba9b9541cd974e6d66df3007c11736fc0
   > Blocks: 0            Seconds: 9
   > contract address:    0x8835A27ed2Cc5f932a7750adfdC3324Ef5a001d5
   > block number:        7122237
   > block timestamp:     1598989425
   > account:             0x542da74EAAC46E67eea6C79926Bd2eCf38FE9123
   > balance:             18.664590253
   > gas used:            306084 (0x4aba4)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00306084 ETH


   'DistributorRole'
   ---------------------------
   > transaction hash:    0xd50b72203b26857bc9a96a40c5faa971ee7169c1d0021bc6467cc96aae547572
   > Blocks: 1            Seconds: 12
   > contract address:    0x7915A5a430c89A1f7A0C60B8F053eD7070cfaD70
   > block number:        7122238
   > block timestamp:     1598989440
   > account:             0x542da74EAAC46E67eea6C79926Bd2eCf38FE9123
   > balance:             18.661529533
   > gas used:            306072 (0x4ab98)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00306072 ETH


   'RetailerRole'
   ------------------------
   > transaction hash:    0xa613e7b152a5a66dd56eceeb9d95bdc539e26860da3e271b2cd2aaca3c18ed2f
   > Blocks: 1            Seconds: 5
   > contract address:    0xC82eA35bEbfac142C594f5911dCe26c226182F1E
   > block number:        7122239
   > block timestamp:     1598989455
   > account:             0x542da74EAAC46E67eea6C79926Bd2eCf38FE9123
   > balance:             18.658468693
   > gas used:            306084 (0x4aba4)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00306084 ETH

  'ConsumerRole'
   ------------------------
   > transaction hash:    0xf8632f77ed243c51d6c0fac6da63a26dab6c5dae50f02e3bf8d7f8ef4fc6d69d
   > Blocks: 0            Seconds: 5
   > contract address:    0x70784dA0F8430D778079bFa2bAA427C757525c56
   > block number:        7122240
   > block timestamp:     1598989470
   > account:             0x542da74EAAC46E67eea6C79926Bd2eCf38FE9123
   > balance:             18.655407853
   > gas used:            306084 (0x4aba4)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00306084 ETH


   'SupplyChain'
   -----------------------
   > transaction hash:    0x3ab137c6d284a653726d476e78818353ae56a74f38ce1f72d57efb01be715390
   > Blocks: 0            Seconds: 5
   > contract address:    0xaB80469a7BF2F4B949E6630bC2Cae5dF8c60a3F0
   > block number:        7122241
   > block timestamp:     1598989485
   > account:             0x542da74EAAC46E67eea6C79926Bd2eCf38FE9123
   > balance:             18.624782083
   > gas used:            3062577 (0x2ebb31)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.03062577 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.04286901 ETH

## Built With

node version number - v12.18.2
Truffle version number - v5.1.39  
web3 version number - v1.2.1


