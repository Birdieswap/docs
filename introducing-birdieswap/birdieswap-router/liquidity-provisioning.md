---
icon: layer-plus
---

# Liquidity Provisioning

The Liquidity Provision service provided by Birdieswap is not an independently operated AMM or vault. Rather, it orchestrates deposits into rigorously vetted yield protocols and pairs the resulting **receipt tokens (Proof Tokens)** as liquidity on a vetted DEX via the Birdieswap router. As with conventional AMMs, the provider must supply the tokens required by the target pair.

Under a conventional flow, an LP would first acquire each side’s receipt token by depositing base assets into the respective underlying protocols, then contribute those receipt tokens as an AMM pair—managing multiple approvals, conversions, and accounting details along the way.

To simplify this process, Birdieswap offers the **Birdieswap router**.

<figure><img src="https://docs.birdieswap.com/~gitbook/image?url=https%3A%2F%2F120790481-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F2EIYgv4Bq81MyOL5UyTz%252Fuploads%252FqfrOpGQfzksvy6s5C73z%252FSlide1.jpeg%3Falt%3Dmedia%26token%3D95c8575b-ef4f-4e4c-9c2b-8b59c06442be&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=42e28f15&#x26;sv=2" alt=""><figcaption></figcaption></figure>

1. The user selects a pair of token from the Pool List and enters the deposit amounts for each token, then clicks the “Start Farming” button.
2. The wallet prompts for transaction approval as in a typical DEX operation.
3. The two tokens forming the pair are individually deposited into their corresponding protocol pools through the internal Single Token Vaults, each receiving its own receipt token.
4. These receipt tokens are automatically stored and processed to issue Birdieswap receipt tokens, analogous to the Single Token Farming process.
5. The two Birdieswap receipt tokens are then paired in the designated Dual Vault and supplied as liquidity to the DEX, using predetermined parameters for the liquidity range and fee rate.
6. The LP tokens received from the DEX are likewise automatically farmed, and corresponding Birdieswap LP tokens are issued to the user, completing the liquidity supply process.
7. Subsequently, Birdieswap uses the ownership of the stored receipt tokens to automatically farm both the individual Single Token yields and the trading fee income, thereby compounding the benefits for the user.
