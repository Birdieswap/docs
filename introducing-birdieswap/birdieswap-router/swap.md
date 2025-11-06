---
icon: rotate
---

# Swap

The Swap service provided by Birdieswap is not an independently operated AMM DEX. Rather, it leverages liquidity supplied via the Birdieswap router to conduct transactions on a rigorously vetted DEX. However, as with conventional AMMs, the user must hold tokens that are paired for the swap.

Since liquidity supplied through Birdieswap consists of receipt tokens obtained from depositing assets into an underlying protocol, a swap would conventionally require that the user obtains the corresponding receipt tokens from that same protocol.

To simplify this complex process, Birdieswap offers the Birdieswap router.

<figure><img src="https://docs.birdieswap.com/~gitbook/image?url=https%3A%2F%2F120790481-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F2EIYgv4Bq81MyOL5UyTz%252Fuploads%252FvxX3pLgYQ3Rse2GgUkZh%252FSlide3.jpeg%3Falt%3Dmedia%26token%3Dbc149d43-0bd8-44b9-8ef5-6de4c532aa34&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=b1245ef&#x26;sv=2" alt=""><figcaption></figcaption></figure>

1. Through a virtual DEX interface provided by Birdieswap, the user selects the token they hold and the desired token to receive, then enters the swap amount. From the user’s perspective, both the token being exchanged and the token received are underlying tokens.
2. As with any conventional DEX (such as Uniswap), the user first authorizes the token usage.
3. Once the authorization is complete, the Swap button is activated. For explanatory purposes, let us denote the token held by the user as Token0 and the token to be received as Token1.
4. The Swap Module accepts Token0 and deposits it via the corresponding Single Token Vault (Vault0) into the underlying protocol’s Token0 pool, receiving a receipt token (Receipt Token0) and issuing a corresponding Birdieswap receipt token.
5. The Birdieswap receipt token for Token0 is then exchanged within the liquidity pool for the Birdieswap receipt token corresponding to Token1.
6. This exchanged Birdieswap receipt token is then converted back (via the appropriate Single Token Vault0, Vault1) into Receipt Token1, which is subsequently redeemed from the underlying protocol’s Token1 pool as Token1(underlying).
7. Token1(underlying) is finally transferred to the user, completing the swap process.
8. The user can then verify the received amount of Token1 in their connected wallet.

Though the process is complex, Birdieswap’s automation ensures that the only manual steps are the initial configuration, token approval, and the final button click—keeping the overall user experience straightforward and user-friendly.
