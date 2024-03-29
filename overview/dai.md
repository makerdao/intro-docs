{% hint style="warning" %} This documentation describes certain core aspects of MakerDAO's protocol that could change over time. Be aware that parts may be inaccurate or out of date. {% endhint %}

# Dai Stablecoin

Dai is an ERC-20 token native to the Ethereum Blockchain. Dai is a stable, fully collateralized, and decentralized currency pegged to the value of the U.S. Dollar and kept stable through a framework of aligned financial incentives. 

Dai is held in digital wallets and supported on Ethereum and other popular blockchains. Dai can be used in the same manner as any other cryptocurrency: It can be freely sent to others, used as payment for goods and services, be held as a hedge against market volatility, and more. All Dai transactions are publicly viewable.

A combination of stable collateral and an excess of volatile collateral backs every Dai in circulation. Under normal circumstances, the value of the collateral backing Dai will always equal or exceed the value of the Dai in circulation. The types, amount, and value of collateral backing Dai are publicly visible on the Ethereum blockchain in real time.

## Why Dai?

A decentralized digital economy needs stable money in order to function. Dai is a price-stable asset that can be used as a medium of exchange, store of value, and unit of account.

Dai enables a wide range of financial activities and applications that have previously been impracticable due to the volatility of legacy cryptocurrencies like Bitcoin.

Dai is the world's first unbiased stable currency that does not discriminate. Any individual or business can realize the advantages of digital money. No one can forcefully seize nor freeze Dai.

## How does Dai stay stable?

Dai is not a hard-pegged currency, so it does not perfectly track the value of the U.S. dollar. Rather, it maintains a free-floating peg that experiences extremely low volatility against the U.S. dollar.

Dai achieves stability through a combination of external market forces, economic incentive mechanisms, and policy tools controlled by MKR token holders. Many different market actors behaving in a self-interested manner contribute to its stability.

There are four primary mechanisms Dai uses to remain stable.

### Peg Stability Modules

The Maker Protocol uses contracts called PSMs (Peg Stability Modules) that allow Dai to be directly redeemed for other cryptocurrencies pegged to the U.S. dollar.

At any time, any user can receive minted Dai in exchange for these cryptocurrencies. If a Peg Stability Module contains sufficient stock, any user can destroy Dai in exchange for receiving these cryptocurrencies.

This mechanism is the most effective at maintaining the Dai peg in the short term.

For more information about the PSM, please refer to the [Maker Manual](https://manual.makerdao.com/module-index/module-psm).

### Maker Vaults

Maker Vaults have a crucial role as they enable the generation of Dai by locking up collateral. This process significantly affects the total Dai supply and ensures transparency and auditability. Vaults maintain overcollateralization using a Liquidation Ratio to protect Dai's backing from volatile collateral devaluation. Additionally, a debt ceiling is enforced to limit exposure to risky or illiquid collaterals. Stability Fees are imposed on Dai generators to effectively manage the peg, fund Maker Protocol development and maintenance, and incentivize active participation in governance.


### Vaults Stability Fees

When creating Dai using Maker Vaults, the vault owner pays an ongoing Stability Fee. Maker Governance can increase or decrease these fees. These fee adjustments can be used to encourage owners of Maker Vaults to create or destroy Dai due to an increased or decreased ongoing cost. In this way, Maker Governance can affect the _supply_ of Dai.

This mechanism is most effective at maintaining the Dai peg in the medium/long term.

###  The Dai Savings Rate

The Dai Savings Rate (DSR) serves as an interest rate offered to Dai holders who choose to deposit their Dai into the DSR smart contract. This incentivizes users to retain their Dai within the system, as they earn rewards for doing so. As a dynamic parameter subject to governance by MKR token holders, the DSR can be adjusted based on market conditions and protocol requirements. This mechanism allows to manage the demand for Dai and contributes to the overall stability and resilience of the MakerDAO platform.

This mechanism is most effective at maintaining the Dai peg in the medium/long term.

### Global Settlement

MKR Holders can decide to shut down the Maker Protocol in order to protect its users, this is known as Global Settlement. At Global Settlement, Dai can be redeemed directly for $1 of collateral that backs it.

This mechanism is primarily a game-theoretical fallback, meant only to be used if other mechanisms have failed. The existence of global settlement contributes to the success of the other mechanisms by providing confidence to market participants that Dai will always be worth $1.