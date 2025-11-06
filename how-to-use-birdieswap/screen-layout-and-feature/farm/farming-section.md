---
icon: wheat
---

# Farming Section

The **Farming Section** manages **liquidity provision and withdrawal** within Birdieswap. You can **add liquidity** under the **Start Tab**, and **withdraw liquidity** under the **Stop Tab**.

<figure><img src="https://crypttempo.gitbook.io/birdieswap/~gitbook/image?url=https%3A%2F%2F3718254475-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fl809DnxvErlAtMYeaBDi%252Fuploads%252FgCWBawO2Yc7G10nNmCDX%252F%25E1%2584%2589%25E1%2585%25B3%25E1%2584%258F%25E1%2585%25B3%25E1%2584%2585%25E1%2585%25B5%25E1%2586%25AB%25E1%2584%2589%25E1%2585%25A3%25E1%2586%25BA%25202025-10-14%2520%25E1%2584%258B%25E1%2585%25A9%25E1%2584%2592%25E1%2585%25AE%252012.10.53.png%3Falt%3Dmedia%26token%3Dd123b939-741f-4cb5-94b5-e54ee2ce325e&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=36a1acfd&#x26;sv=2" alt=""><figcaption></figcaption></figure>

***

**Start Farming**

The **Start Farming Panel** consists of three components:

1. **ETH–WETH Slider**
2. **Amount Setting Section**
3. **Execute Button Section**

***

**① ETH–WETH Slider**

This slider appears when the selected pool includes **ETH** as one of its paired tokens. It allows you to choose whether to use **ETH** or **WETH** when providing liquidity. If the pool does **not** contain ETH, this slider will not appear.

***

**② Amount Setting Section**

Here, you set the amount of tokens you want to provide as liquidity.

* When you enter an amount for one token, the other token’s amount is automatically calculated based on the current **exchange rate**.
* Clicking **Max** sets the maximum supply amount based on the **token with the lower total value** in your wallet.

***

**③ Execute Button Section**

If the entered token amounts **exceed their approved allowances**, the **Approve Button** becomes active. Click **Approve** to grant Birdieswap permission to use those tokens.

Once both tokens are approved and the entered amounts are valid, the **Start Farming Button** becomes active. Clicking this button begins the liquidity provision process for the selected pool.

If no amount is entered, or if the amount exceeds your available token balance, a warning message appears below the button:

* `"Enter an amount"` — when the field is empty
* `"Insufficient (Token Symbol) balance"` — when your entered amount exceeds your balance

***

**Stop Farming**

The **Stop Farming Panel** consists of four components:

1. **ETH–WETH Slider**
2. **Amount Setting Section**
3. **Receive Summary Section**
4. **Execute Button Section**

***

**① ETH–WETH Slider**

This slider appears when the selected pool includes **ETH**. It lets you choose whether to **receive ETH or WETH** upon withdrawal. If the pool does not contain ETH, this slider will not appear.

***

**② Amount Setting Section**

Here, you specify the number of **LP Tokens** you want to withdraw. You can only withdraw up to the amount of LP Tokens you currently hold. Click **Max** to automatically fill in your total available LP Token balance.

***

**③ Execute Button Section**

If the entered LP Token amount **exceeds your allowance**, the **Approve Button** becomes active. Click **Approve** to grant usage permission for those tokens.

Once the LP Token amount is set and the approval is complete, the **Stop Farming Button** becomes active. Clicking it withdraws liquidity from the selected pool.

If no amount is entered or the entered amount exceeds your available LP Token balance, the following warnings appear below the button:

* `"Enter an amount"` — when no amount is entered
