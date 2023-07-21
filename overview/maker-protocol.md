{% hint style="warning" %} This documentation describes certain core aspects of MakerDAO's protocol that could change over time. Be aware that parts may be inaccurate or out of date. {% endhint %}

# Maker Protocol

The Maker Protocol is a set of modular [smart contracts](https://ethereum.org/en/smart-contracts/) that exist primarily on the Ethereum blockchain. 

These contracts define the following (non-exhaustive):
* The DAI Stablecoin 
* The MKR token
* The Maker Vault Engine
* The interactions between these elements that result in a stable system.

## How does the Maker Protocol Work?

Actions that affect the Maker Protocol are either permissionless or permissioned. Any entity interacting with the Ethereum blockchain can perform permissionless actions. The governance smart contract can only perform permissioned actions after a successful vote by MKR Holders.    

Permissionless actions in the Maker Protocol include things like:
* Opening a Maker Vault according to the rules of the Maker Protocol.
* Calling necessary maintenance functions.
* Liquidating a vault user according to the rules of the Maker Protocol.

Permissioned actions taken by Maker Governance include things like:
* Changing the risk parameters on a certain class of vault.
* Adjusting liquidation and auction parameters.
* Transferring DAI owned by the Maker Protocol.
* Upgrading or replacing parts of the Maker Protocol.

DAI and Vaults are accessible only to their respective owners.  

No entity or individual has permissions or direct control over any aspect of the Maker Protocol.  

## How does this relate to our other concepts?

The DAI Stablecoin, MKR token and Maker Vaults are all a part of the Maker Protocol.  

MKR Token Holders govern the Maker Protocol.  

MakerDAO is the group of individuals and entities that own the MKR token and/or operate, maintain and improve the Maker Protocol.  

![](https://github.com/makerdao/intro-docs/media/basic-overview.png)
