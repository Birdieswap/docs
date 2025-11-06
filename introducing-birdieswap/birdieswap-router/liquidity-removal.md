---
icon: layer-minus
---

# Liquidity Removal

The liquidity withdrawal service provided by Birdieswap is not an independently operated AMM or vault. Rather, it orchestrates the unwind of positions from rigorously vetted yield protocols and removes the paired receipt-token liquidity from a vetted DEX via the Birdieswap router. As with conventional AMMs, the provider withdraws from the paired assets of the target pool. Under a conventional flow, an LP would first retrieve the LP tokens from the DEX, dissolve the position into the two receipt tokens, redeem each from its underlying protocol back to the native assets, and manually manage multiple approvals, conversions, and accounting steps. To simplify this process, Birdieswap offers the Birdieswap router.

<figure><img src="https://crypttempo.gitbook.io/birdieswap/~gitbook/image?url=https%3A%2F%2F3718254475-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fl809DnxvErlAtMYeaBDi%252Fuploads%252Fo7eINqx477THm5GFvUhE%252Fimage.png%3Falt%3Dmedia%26token%3Da6a4b5ac-f297-49ae-b44b-7b5e5c318b86&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=87fc5a95&#x26;sv=2" alt=""><figcaption></figcaption></figure>

1. The user selects the active pair from the Pool List, specifies the withdrawal amount, and clicks the “Stop Farming” button.
2. The wallet prompts for transaction approval as in a typical DEX operation.
3. The user’s Birdieswap LP tokens are **submitted back to the router**, which **retrieves the corresponding LP tokens from the DEX** and begins the unwind.
4. The DEX LP tokens are removed, automatically splitting the position into the two Birdieswap receipt tokens for the pair.
5. These Birdieswap receipt tokens are converted through the internal Single Token Vaults into the underlying protocols’ receipt tokens (Proof Tokens).
6. Each Proof Token is redeemed in its respective underlying protocol for the **native assets** (Token0 and Token1).
7. The redeemed native tokens are transferred to the user’s wallet, completing the withdrawal process.
8. Throughout the unwind, Birdieswap uses the ownership of the stored receipt tokens to settle accrued single-token yield and trading-fee income, so the user receives principal plus realized earnings.
