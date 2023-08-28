{% hint style="warning" %} This documentation describes certain core aspects of MakerDAO's protocol that could change over time. Be aware that parts may be inaccurate or out of date. {% endhint %}

# Maker Vaults

Maker vaults are a tool of the Maker Protocol through which users can mint (create) Dai against locked-up collateral.

Users mint Dai by leveraging collateral and repay Dai (which is burned) to retrieve their collateral. This on-chain process ensures complete auditability of circulating Dai and its collateral support.

Vaults must be sufficiently overcollateralized relative to Dai borrowed using that vault (according to the [Liquidation Ratio](https://manual.makerdao.com/parameter-index/vault-risk/param-liquidation-ratio) parameter). If they are not sufficiently overcollateralized at any time, their collateral is liquidated and sold to cover the Dai backed by it. This safeguards Dai's backing from volatile collateral devaluation.

Additionally, a [Debt Ceiling](https://manual.makerdao.com/parameter-index/vault-risk/param-debt-ceiling) is imposed on each vault type to prevent over-reliance on risky or illiquid collaterals.

Vault owners who mint Dai incur a [Stability Fee](https://manual.makerdao.com/parameter-index/vault-risk/param-stability-fee) on their balance. These fees are used to fund the protocol and accrue value to MKR holders, as it funds the development and maintenance of the protocol while contributing to the growth of value for MKR holders.

## RWA Vaults

RWA (Real-World Asset) vaults enable users to collateralize real-world assets, which are first tokenized to generate Dai. Unlike traditional collateral limited to digital assets, RWA vaults broaden protocol's scope, enhancing diversification and stability.

These vaults undergo rigorous risk assessment and governance approval, ensuring compliance with MakerDAO's strict criteria for collateral security and stability. 

## Why Open a Vault?

Vaults let users access the underlying value of their assets while avoiding the need to sell them.

**Leverage**

Speculators can use decentralized leverage to amplify exposure to an asset by investing Dai generated from their vault. Caution is advised as it intensifies both the risk of loss and the potential for gains.

**Draw Liquidity from Your Assets**

Users looking for liquidity can turn to vaults since Dai can serve any purpose. Users can generate Dai using their cryptocurrency assets to cover expenses while keeping their exposure to assets in their vaults.

**Flexible Repayment Schedule**

Vaults offer flexible terms. There are no repayment schedules, minimum payments, or credit history requirements. Users can repay at their own pace as long as their vault is properly collateralized. 


{% hint style="warning" %} 

Any use case of vaults is associated with various risks, such as [Liquidation Penalty](https://manual.makerdao.com/parameter-index/vault-risk/param-liquidation-penalty). Every user should have a good understanding of the risks applicable in their situation. 