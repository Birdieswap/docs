# Swap

The Swap service provided by Birdieswap is not an independently operated AMM DEX. Rather, it leverages liquidity supplied via the Birdieswap router to conduct transactions on a rigorously vetted DEX. However, as with conventional AMMs, the user must hold tokens that are paired for the swap.

Since liquidity supplied through Birdieswap consists of receipt tokens obtained from depositing assets into an underlying protocol, a swap would conventionally require that the user obtains the corresponding receipt tokens from that same protocol.

To simplify this complex process, Birdieswap offers the Birdieswap router.

<figure><img src="https://content.gitbook.com/content/lZQrEn5MW0lM7mThH3ST/blobs/QqRbH1qwIe4E93mm5oHr/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202024-06-25%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%202.09.45.png" alt=""><figcaption></figcaption></figure>

1. Through a virtual DEX interface provided by Birdieswap, the user selects the token they hold and the desired token to receive, then enters the swap amount. From the user’s perspective, both the token being exchanged and the token received are native tokens.
2. As with any conventional DEX (such as Uniswap), the user first authorizes the token usage.
3. Once the authorization is complete, the Swap button is activated. For explanatory purposes, let us denote the token held by the user as Token1 and the token to be received as Token2.
4. The Swap Module accepts Token1 and deposits it via the corresponding Single Token Vault (Vault1) into the underlying protocol’s Token1 pool, receiving a receipt token (Receipt Token1) and issuing a corresponding Birdieswap receipt token.
5. The Birdieswap receipt token for Token1 is then exchanged within the liquidity pool for the Birdieswap receipt token corresponding to Token2.
6. This exchanged Birdieswap receipt token is then converted back (via the appropriate Single Token Vault, Vault2) into Receipt Token2, which is subsequently redeemed from the underlying protocol’s Token2 pool as Native Token2.
7. Native Token2 is finally transferred to the user, completing the swap process.
8. The user can then verify the received amount of Token2 in their connected wallet.

Though the process is complex, Birdieswap’s automation ensures that the only manual steps are the initial configuration, token approval, and the final button click—keeping the overall user experience straightforward and user-friendly.
