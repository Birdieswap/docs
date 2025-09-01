# Farming

The Birdieswap router is also responsible for all farming operations within Birdieswap. It is composed of various Single Token Vaults and Pair Token(LP) Vaults that connect to protocols offering diversified yield opportunities for each token. Through the router, users can easily engage in Pair Token(LP) Farming.

<figure><img src="https://content.gitbook.com/content/lZQrEn5MW0lM7mThH3ST/blobs/8LwFzkDUbOHILIH4GsAe/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202024-06-20%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%201.34.42.png" alt=""><figcaption></figcaption></figure>

* Single Token Farming: This service leverages lending protocols or similar mechanisms to generate yield from individual tokens, much like first-generation Yield Farming Aggregators. The system automatically harvests rewards at set intervals and reinvests them, enabling the power of compounding. However, this is only used for internal use, as a part of the Pair Token Farming.
* Pair Token Farming: In this model, receipt tokens corresponding to each individual token are paired and supplied as liquidity to a chosen DEX. As a result, users earn both the yield from Single Token Farming and the trading fee income from the paired tokens. This service also supports automated harvesting and reinvestment to realize compound returns.

## Multi-Token Reward–Enabled Vault

Birdieswap’s vaults support Multi-Token Rewards—in other words, they enable the distribution of several types of tokens as rewards. Depending on the token, timing, or operational strategy, users may receive additional yield opportunities through the allocation of multiple tokens as rewards.
