---
icon: hand-wave
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# Welcome to Birdieswap

<figure><img src=".gitbook/assets/Birdieswap_Intro (1).png" alt=""><figcaption></figcaption></figure>

Birdieswap is a next-generation DeFi interface that unlocks Dual Yield — letting the same capital earn **deposit yields** _and_ **trading fees**.

We operate as a router layer that unifies lending/vaults and AMMs into one seamless liquidity surface. The result: LPs earn more on the same dollars, and traders swap exactly like they do on any DEX.

## What is Birdieswap doing?

DeFi is powerful, but it still feels fragmented — capital sits in yield vaults while trading happens elsewhere. Users must choose between earning and using their assets.

Birdieswap brings these worlds together. With our Dual-Yield Architecture, one unit of capital can work twice:

* Vault yield from integrated protocols, and
* Swap fees from trades routed through Birdieswap.

From the user’s perspective, nothing feels different: swaps happen in familiar tokens, slippage and fees look normal, and confirmations are instant. Behind the scenes, Birdieswap’s router handles the complexity for you.

## Under the hood (at a glance)

* btoken standard. Yield-bearing receipt tokens from vaults are standardized as btokens so they can live natively inside AMM pools.
* Router intelligence. When a trader swaps USDC → WBTC, our router automatically wraps/unwraps at the edges, so the trade clears against a btoken pair without extra clicks or steps.
* Price fairness. The router respects each vault’s share value, helping pools track fair value as yields change — while preserving a familiar trading UX.

## Who is Birdieswap for?

* Traders: Just swap. Same tokens, same flow. The router abstracts the rest.
* LPs: Provide liquidity to btoken pairs and earn dual yield: vault APR + AMM fees.
* Integrators: A clean, composable interface for wallets, aggregators, and protocols.

## Birdieswap’s Goals

* Dual-Yield Accessibility\
  Make dual earnings a single, seamless action for everyone.
* Router-Level Innovation\
  Treat yield-bearing assets as first-class citizens in swap paths via btokens — so assets keep earning even while being traded.
* Sustainable Liquidity Flywheel\
  More yield → deeper liquidity → better pricing → more flow — a loop that strengthens the entire ecosystem.



Birdieswap exists to make liquidity smarter, earning effortless, and DeFi more composable for everyone.

## Disclaimer

While users may engage in yield farming by utilizing the smart contracts provided on the Birdieswap website, please note that returns are determined by the third-party protocols selected as underlying investment targets, and thus, the principal is not guaranteed to be 100%.

Birdieswap does not manage, custody, or hold ownership of your assets. Although the team have been working with best efforts to minimize vulnerabilities, there may still exist as-yet undiscovered issues.

Users must fully acknowledge and assume complete responsibility for their use of Birdieswap, including any losses incurred as a result of its operation. Furthermore, all information contained in this document is provided solely for educational purposes; Birdieswap does not offer any investment recommendations or advice.
