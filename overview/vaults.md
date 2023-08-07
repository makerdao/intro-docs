{% hint style="warning" %} This documentation describes certain core aspects of MakerDAO's protocol that could change over time. Be aware that parts may be inaccurate or out of date. {% endhint %}

# Maker Vaults

Maker Vaults are a tool of the Maker Protocol through which users can create (mint) Dai against locked-up collateral.

Users generate Dai by leveraging collateral and repay Dai to destroy their generated balance. This on-chain process ensures complete auditability of circulating Dai and its collateral support.

Vaults are overcollateralized with a [Liquidation Ratio](https://manual.makerdao.com/parameter-index/vault-risk/param-liquidation-ratio) maintained by owners to prevent collateral liquidation. This safeguards Dai's backing from volatile collateral devaluation.

Additionally, a [debt ceiling](https://manual.makerdao.com/parameter-index/vault-risk/param-debt-ceiling) is imposed on each Vault type to prevent over-reliance on risky or illiquid collaterals.

Vault owners who mint Dai incur a [Stability Fee](https://manual.makerdao.com/parameter-index/vault-risk/param-stability-fee) on their balance. These fees manage the peg, fund Maker Protocol development, maintenance, and reward its governors.


## RWA Vaults

RWA (Real-World Asset) vaults enable users to collateralize real-world assets, like invoices and real estate, to generate Dai. Unlike traditional collateral limited to digital assets, RWA vaults broaden protocol's scope, enhancing diversification, stability, and financial inclusion.

These vaults undergo rigorous risk assessment and governance approval, ensuring compliance with MakerDAO's strict criteria for collateral security and stability. 

## Why Open a Vault?

Vaults let users access the underlying value of their assets while avoiding the need to sell them.

**Leverage**

Speculators can use decentralized leverage to amplify exposure to an asset by investing Dai generated from their Vault. Caution is advised as it intensifies both the risk of loss and the potential for gains.

**Draw Liquidity from Your Assets**

Users looking for liquidity can turn to Vaults since Dai can serve any purpose. Users can generate Dai using their cryptocurrency assets to cover expenses while keeping their exposure to those assets.

**Flexible Repayment Schedule**

Vaults offer flexible terms. There are no repayment schedules, minimum payments, or credit history requirements. Users can repay at their own pace as long as their Vault is properly collateralized. 


{% hint style="warning" %} 

Any use case of Vaults is associated with various risks. Every user should have a good understanding of the risks applicable in their situation. These risks are covered in [the following documentation](https://manual.makerdao.com/parameter-index/vault-risk). 