---
description: The Core Engine for Yield-Bearing Swaps
icon: arrow-progress
---

# Birdieswap Router

At the heart of Birdieswap is the **Birdieswap Router**. The router does not run its own AMM or create pools. Instead, it **orchestrates** interactions between underlying yield protocols and a DEX, executing deposits, conversions, liquidity management, and settlement **atomically on-chain**. From a user’s point of view, Birdieswap feels as simple as a standard Uniswap-style interface because the router absorbs the internal complexity—approvals, deposits, conversions, and accounting—into a single coherent flow.

#### What the router actually does <a href="#what-the-router-actually-does" id="what-the-router-actually-does"></a>

* **Standardizes receipt tokens.** When assets are deposited into underlying protocols, protocol-specific receipt tokens are issued. The router standardizes them into Birdieswap receipt tokens so they can be paired for liquidity or swapped efficiently.
* **Builds yield-bearing liquidity positions.** The router pairs the Birdieswap receipt tokens for both sides in a Dual Vault and supplies them as liquidity to a DEX with predefined parameters (range, fee tier). This structure accrues **both the protocol’s yield and the DEX’s trading fees** at the same time.
* **Orchestrates yield-bearing swaps.** For swaps, the router deposits the user’s source asset into its designated underlying protocol to mint a receipt token, performs the exchange at the receipt-token layer, converts the result back through the appropriate vault, and delivers the **native target asset** to the wallet. Externally it behaves like a familiar single-click swap, while the deposit → standardize → swap → redeem path is handled internally.
* **Unwinds positions cleanly.** For withdrawals, the router collects the DEX LP tokens corresponding to the user’s position, removes liquidity into the two Birdieswap receipt tokens, converts each back to the underlying protocols’ receipt tokens, redeems them to native assets, and returns those assets to the user—**settling accrued yield and trading fees** in the process.
* **Atomicity, simplification, consistent accounting.** Because the router executes all steps atomically on-chain, it reduces intermediate-state risk and manual coordination while keeping earnings and accounting consistent end-to-end.

In short, the Birdieswap Router is the **engine** that makes it practical to earn yield and trading fees simultaneously, while presenting an interface as straightforward as a conventional DEX. **Next, we will walk through the detailed flows and diagrams for liquidity provision, withdrawal, and swap.**

