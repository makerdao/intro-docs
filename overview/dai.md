{% hint style="warning" %} This documentation describes certain core aspects of MakerDAO's protocol that could change over time. Be aware that parts may be inaccurate or out of date. {% endhint %}

# Dai Stablecoin

Dai is a stable, fully collateralized, and decentralized currency pegged to the value of the U.S Dollar and kept stable through a framework of aligned financial incentives. 

Dai is held in digital wallets and supported on Ethereum and other popular blockchains. Dai can be is used in the same manner as any other cryptocurrency: It can be freely sent to others, used as payment for goods and services, be held as a hedge against market volatility, and more. All Dai transactions are publicly viewable.

A combination of stable collateral and an excess of volatile collateral backs every Dai in circulation. Under normal circumstances, the value of the collateral backing Dai will always equal or exceed the value of the Dai in circulation. The types, amount and value of collateral backing Dai are publicly visible on the Ethereum blockchain in real time.

## Why Dai?

A decentralized digital economy needs stable money in order to function. Dai is a price-stable asset that can be used as a medium of exchange, store of value, and unit of account.

Dai enables a wide range of financial activities and applications that have previously been untenable due to the volatility of legacy cryptocurrencies like Bitcoin.

Dai is the world's first unbiased, stable currency that does not discriminate. Any individual or business can realize the advantages of digital money.

## How does Dai stay stable?

Dai is not a hard-pegged currency, so it does not perfectly track the value of the U.S Dollar. Rather, it maintains a free-floating peg that experiences extremely low volatility against the US dollar.

Dai achieves stability through a combination of external market forces, economic incentives, and policy tools controlled by MKR token holders. Many different market actors behaving in their own self-interest, contribute to its stability.

There are four primary mechanisms Dai uses to remain stable.

### Peg Stability Modules

The Maker Protocol uses contracts called a Peg Stability Modules that allow Dai to be directly redeemable for other U.S Dollar backed cryptocurrencies. 

At any time, any user can receive minted Dai in exchange for these cryptocurrencies. If a Peg Stability Module contains sufficient stock, any user can destroy Dai in exchange for receiving these cryptocurrencies. 

This mechanism is the most effective at maintaining the Dai peg in the short term. 

### Vault Stability Fees

When creating Dai using Maker Vaults, the vault owner pays an ongoing Stability Fee. Maker Governance can increase or decrease these fees on a general level. These fee adjustments can be used to encourage owners of Maker Vaults to create or destroy Dai due to an increased or decreased ongoing cost. In this way, Maker Governance can affect the _supply_ of Dai.

This mechanism is most effective at maintaining the Dai peg in the medium/long term.

###  The Dai Savings Rate

Maker Governance can set the Dai Savings Rate. The Dai Savings Rate is a paid to any Dai holder that wishes to receive it via another smart contract; it rewards users for holding Dai. In this way, Maker Governance can affect the _demand_ for Dai. 

This mechanism is most effective at maintaining the Dai peg in the medium/long term.

### Global Settlement

Finally, Maker Governance can decide to shut down the Maker Protocol in order to protect the Dai peg, this is known as Global Settlement. At Global Settlement, Dai can be redeemed directly for $1 of collateral that backs it.

This mechanism is primarily a game-theoretical fallback, meant to only be used if other mechanisms have failed. The existence of global settlement contributes to the success of the other mechanisms by providing confidence to market participants that Dai will always be worth $1.