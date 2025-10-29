# Swap Tokens

Token swaps are performed on the **Swap Page**. The process works just like other decentralized exchanges (DEXs), but in this tutorial, we’ll go through **every available feature** on Birdieswap to help you get comfortable with the full swapping experience.

the full swapping experience.

***

**1. Setting Up the Swap**

Follow these steps to configure your swap parameters:

① Click the **Select Token** button (available for both _Sell_ and _Buy_).

* By default, the _Sell Token_ is set to **ETH**, but you can change it to any other token.

② In the **Select a Token** pop-over, choose the token you wish to use and click to select it.

③ Enter the **amount** you want to swap in one of the input fields (_Sell_ or _Buy_).

* The corresponding value in the other field is automatically calculated based on the current exchange rate.

④ Click the **Settings Button** at the top-right corner to open the **Max Slippage Settings** window.

⑤ The default setting is **Auto (0.5%)**, but you can manually enter a custom value.

<figure><img src="https://crypttempo.gitbook.io/birdieswap/~gitbook/image?url=https%3A%2F%2F3718254475-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fl809DnxvErlAtMYeaBDi%252Fuploads%252Fs0XhDRajUno5KNBWl2G4%252F%25E1%2584%2589%25E1%2585%25B3%25E1%2584%258F%25E1%2585%25B3%25E1%2584%2585%25E1%2585%25B5%25E1%2586%25AB%25E1%2584%2589%25E1%2585%25A3%25E1%2586%25BA%25202025-10-15%2520%25E1%2584%258B%25E1%2585%25A9%25E1%2584%2592%25E1%2585%25AE%252012.10.01.png%3Falt%3Dmedia%26token%3Df856a3c1-2a97-46a0-a6d5-ff21f49aaaea&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=9ab91036&#x26;sv=2" alt=""><figcaption></figcaption></figure>

In this tutorial, we’ll set up the following example:

* **Sell Token:** USDC
* **Buy Token:** WETH
* **Swap Amount:** 1,000 USDC
* **Max Slippage:** 1%

Once these values are entered, your swap configuration is complete and should look similar to the sample below.

***

**2. Approving Token Usage**

Before executing the swap, you must **approve Birdieswap to use your tokens** — this allows the protocol to access the tokens required for the trade.

If a **lock icon** appears next to the Sell Token logo and the **Approve Button** is active, token approval is required.

<figure><img src="https://crypttempo.gitbook.io/birdieswap/~gitbook/image?url=https%3A%2F%2F3718254475-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fl809DnxvErlAtMYeaBDi%252Fuploads%252F30mj2oEDwAdCpcntUATe%252F%25E1%2584%2589%25E1%2585%25B3%25E1%2584%258F%25E1%2585%25B3%25E1%2584%2585%25E1%2585%25B5%25E1%2586%25AB%25E1%2584%2589%25E1%2585%25A3%25E1%2586%25BA%25202025-10-29%2520%25E1%2584%258B%25E1%2585%25A9%25E1%2584%2592%25E1%2585%25AE%25206.02.44.png%3Falt%3Dmedia%26token%3Df2b23e18-207d-43c1-a7c1-1559df6898ac&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=d37edaf5&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Follow these steps to approve your token:

① Click the **Approve Button**. ② A **Transaction Status Pop-over** will appear showing _“Confirm Transaction in Wallet”_, along with the specific approval request (e.g., _Approve USDC_). Shortly after, your connected wallet will prompt you to approve the spending limit. ③ In your wallet, the **spending limit request window** opens.

* The default allowance is _Unlimited_, but you can adjust it by clicking the **pencil icon** on the left.
* Review the details and click **Confirm** in the lower-right corner. ④ After confirming, the wallet window closes and the Transaction Status Pop-over updates to _“Transaction Submitted.”_
* You can click **View on Explorer** to check the transaction progress on the blockchain. ⑤ Once the transaction is confirmed, the pop-over changes to _“Success!”_, completing the approval process.
* The **lock icon** and **Approve Button** will disappear, and the **Swap Button** will become active.

***

**3. Executing the Token Swap**

With your swap settings and approval complete, you’re ready to execute the swap.

<figure><img src="https://crypttempo.gitbook.io/birdieswap/~gitbook/image?url=https%3A%2F%2F3718254475-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fl809DnxvErlAtMYeaBDi%252Fuploads%252FcK7zGTZjnhALmvhXlt8X%252F%25E1%2584%2589%25E1%2585%25B3%25E1%2584%258F%25E1%2585%25B3%25E1%2584%2585%25E1%2585%25B5%25E1%2586%25AB%25E1%2584%2589%25E1%2585%25A3%25E1%2586%25BA%25202025-10-29%2520%25E1%2584%258B%25E1%2585%25A9%25E1%2584%2592%25E1%2585%25AE%25206.05.33.png%3Falt%3Dmedia%26token%3D89a26b33-b7e0-462b-9a66-dceacfd65e98&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=9e9fdfa8&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Follow these steps to complete the process:

① Click the **Swap Button**. ② The **Transaction Status Pop-over** will appear again, showing _“Confirm Transaction in Wallet”_ and the swap details you configured.

* Your connected wallet will automatically open a **transaction request** for the swap. ③ Review the transaction details in your wallet — this screen will display the expected changes based on your input.
* Once confirmed, click the **Confirm Button** in the lower-right corner. ④ After confirming, the wallet window closes and the pop-over updates to _“Transaction Submitted.”_
* Click **View on Explorer** to track your transaction status on the blockchain. ⑤ When the swap is complete, the pop-over changes to _“Success!”_, indicating the transaction has been finalized.
* The displayed values now show the **final executed swap amount**.
* You can also verify the full transaction details on the **blockchain explorer**, and your wallet balance will reflect the updated token amounts.
