# Providing Liquidity

**1. Setting Up Liquidity Provision**

Once you’ve decided which pool to provide liquidity to, follow these steps to configure your initial setup:

① Click the **selected liquidity pool** in the **Farm List Table** to open the **Farm Detail** window. ② Liquidity provision is performed in the **Start Tab**.

* Make sure the active tab is **Start**. If it isn’t, click the **Start Tab** to switch. ③ If the selected pool includes **ETH**, choose whether to provide liquidity using **ETH** or **WETH** by clicking your preferred option.
* In this tutorial, we’ll select **WETH**.
* If the pool does not contain ETH, this slider will not appear. ④ Enter the amount of tokens you want to provide in the **input field**.
* When you enter a value for one token, the other is automatically calculated to maintain a **1:1 value ratio**. ⑤ Click **Max** to automatically set the input based on the **maximum amount of the token with the lower total value** in your wallet.

<figure><img src="https://crypttempo.gitbook.io/birdieswap/~gitbook/image?url=https%3A%2F%2F3718254475-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fl809DnxvErlAtMYeaBDi%252Fuploads%252FNXzxZAUYxZJzQkRwnpO0%252F%25E1%2584%2589%25E1%2585%25B3%25E1%2584%258F%25E1%2585%25B3%25E1%2584%2585%25E1%2585%25B5%25E1%2586%25AB%25E1%2584%2589%25E1%2585%25A3%25E1%2586%25BA%25202025-10-15%2520%25E1%2584%258B%25E1%2585%25A9%25E1%2584%2592%25E1%2585%25AE%25202.30.12.png%3Falt%3Dmedia%26token%3D2fda5e4f-65d3-41c5-9f56-93bb9f60a8d9&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=8d5b94f5&#x26;sv=2" alt=""><figcaption></figcaption></figure>

In this tutorial example, we’ll enter **0.5 WETH** as the amount to provide.

***

**2. Approving Token Usage**

Because liquidity provision requires **two tokens**, you’ll need to approve each one before proceeding.

<figure><img src="https://crypttempo.gitbook.io/birdieswap/~gitbook/image?url=https%3A%2F%2F3718254475-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fl809DnxvErlAtMYeaBDi%252Fuploads%252FQs1xM4Ft3KVpNpJP3vEs%252F%25E1%2584%2589%25E1%2585%25B3%25E1%2584%258F%25E1%2585%25B3%25E1%2584%2585%25E1%2585%25B5%25E1%2586%25AB%25E1%2584%2589%25E1%2585%25A3%25E1%2586%25BA%25202025-10-15%2520%25E1%2584%258B%25E1%2585%25A9%25E1%2584%2592%25E1%2585%25AE%25203.20.26.png%3Falt%3Dmedia%26token%3D20de6273-4cd7-4c63-9d56-188e77fc0da5&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=b27d3219&#x26;sv=2" alt=""><figcaption></figcaption></figure>

The approval process is identical to **“2. Approving Token Usage”** in the Swapping Tokens section, so you can refer there for details.

After both tokens are approved, the **lock icons** and **Approve Buttons** will disappear from the input fields, and the **Start Farming Button** will become active.

***

**3. Providing Liquidity**

<figure><img src="https://crypttempo.gitbook.io/birdieswap/~gitbook/image?url=https%3A%2F%2F3718254475-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fl809DnxvErlAtMYeaBDi%252Fuploads%252FN7hx6pyB5EqDr0pcoBB0%252F%25E1%2584%2589%25E1%2585%25B3%25E1%2584%258F%25E1%2585%25B3%25E1%2584%2585%25E1%2585%25B5%25E1%2586%25AB%25E1%2584%2589%25E1%2585%25A3%25E1%2586%25BA%25202025-10-29%2520%25E1%2584%258B%25E1%2585%25A9%25E1%2584%2592%25E1%2585%25AE%25206.12.20.png%3Falt%3Dmedia%26token%3Dd7438de7-8b69-4bba-8b74-5ccf4eedabdf&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=4908f663&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Once setup and approvals are complete, you can now proceed with the actual liquidity provision:

① Click the **Start Farming Button**. ② The **Transaction Status Pop-over** will appear, showing _“Confirm Transaction in Wallet”_ along with your selected liquidity parameters.

* Your connected wallet will automatically prompt a **transaction request** for liquidity provision. ③ In your wallet, review the transaction request window.
* It will show the expected changes, including the **liquidity amounts** you’re adding and the **LP Tokens** you’ll receive.
* After reviewing, click the **Confirm Button** in the lower-right corner. ④ Once confirmed, the wallet window closes and the pop-over updates to _“Transaction Submitted.”_
* Click **View on Explorer** to monitor transaction progress and details. ⑤ When the transaction is confirmed, the pop-over changes to _“Success!”_, completing the liquidity provision.
* The displayed value now shows the **actual LP Token amount received** after the transaction is finalized.
* You can review the full transaction on the **blockchain explorer**, and by clicking **“Add Birdieswap USDC 3000 WETH to wallet”**, you can **register the LP Token** in your wallet for easy tracking.
