# SWAP

The **Swap Page** is where you exchange tokens. It consists of the following sections: **Slippage Section**, **Swap Input Section**, **Execute Button Section**, and the **Swap Fee Info Section**, which appears once your swap settings are complete.

<figure><img src="https://crypttempo.gitbook.io/birdieswap/~gitbook/image?url=https%3A%2F%2F3718254475-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fl809DnxvErlAtMYeaBDi%252Fuploads%252F66GGMkjXbgyUji5DPLVF%252F%25E1%2584%2589%25E1%2585%25B3%25E1%2584%258F%25E1%2585%25B3%25E1%2584%2585%25E1%2585%25B5%25E1%2586%25AB%25E1%2584%2589%25E1%2585%25A3%25E1%2586%25BA%25202025-10-13%2520%25E1%2584%258B%25E1%2585%25A9%25E1%2584%2592%25E1%2585%25AE%25208.12.44.png%3Falt%3Dmedia%26token%3D80f51962-96f4-4d4a-8c7f-7006a041ece8&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=6b781baa&#x26;sv=2" alt=""><figcaption></figcaption></figure>

***

**① Slippage Section**

This section contains the **Slippage Setting Button** and the **display area** for your current slippage value. When the slippage is set to _Auto_, the value is hidden.

Click the **Settings Button** to open the **Max Slippage Configuration** window. You can choose between:

* **Auto** — Default slippage tolerance is set to **0.5%**.
* **Custom** — You can enter any positive number greater than zero as your slippage tolerance.

***

**② Swap Input Section**

The Swap Input Section includes two identical **Input Cards** (for **Sell** and **Buy** tokens) and a **Reverse Button** between them.

Here’s how it works:

* When you enter a token amount in either the _Sell_ or _Buy_ input, the other field automatically updates based on the calculated exchange rate.
* Clicking the **Select Token Button** opens a list of available tokens. Select one to set it as your Sell or Buy token.
* Click **Max** to automatically set the full amount of your available _Sell Token_ balance.
* Click the **Reverse Button** to swap the positions of the Sell and Buy tokens.
* Whenever you change the Sell or Buy token, the entered quantities reset to **zero**.

Below each input, you’ll see two helpful details:

* The **fiat-equivalent value** of the entered amount, and
* The **current balance** of the selected token.

Once all settings are configured, the **Execute Button Section** and **Swap Fee Info Section** become active.

<figure><img src="https://crypttempo.gitbook.io/birdieswap/~gitbook/image?url=https%3A%2F%2F3718254475-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fl809DnxvErlAtMYeaBDi%252Fuploads%252F4wCILHZ9XxbR93EwPdXY%252F%25E1%2584%2589%25E1%2585%25B3%25E1%2584%258F%25E1%2585%25B3%25E1%2584%2585%25E1%2585%25B5%25E1%2586%25AB%25E1%2584%2589%25E1%2585%25A3%25E1%2586%25BA%25202025-10-13%2520%25E1%2584%258B%25E1%2585%25A9%25E1%2584%2592%25E1%2585%25AE%25208.48.49.png%3Falt%3Dmedia%26token%3D558abfea-d05e-4b69-8540-c233c2986cd1&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=bee7494d&#x26;sv=2" alt=""><figcaption></figcaption></figure>

***

**③ Execute Button Section**

This section controls the approval and execution of your swap.

* If the amount entered in the _Sell Token_ field **exceeds your current allowance**, the **Approve Button** becomes active. Clicking it initiates the approval transaction for that token.
* Once your _Sell Token_ has sufficient allowance, the **Swap Button** becomes active.

Before activation, the Swap Button area displays various **status indicators** showing whether all necessary settings are complete. When everything is ready, the button turns into an **active Swap Button**. Clicking **Swap** executes the token exchange according to your configured parameters.

<figure><img src="https://crypttempo.gitbook.io/birdieswap/~gitbook/image?url=https%3A%2F%2F3718254475-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fl809DnxvErlAtMYeaBDi%252Fuploads%252FosksluVg442f6bldYNR7%252F%25E1%2584%2589%25E1%2585%25B3%25E1%2584%258F%25E1%2585%25B3%25E1%2584%2585%25E1%2585%25B5%25E1%2586%25AB%25E1%2584%2589%25E1%2585%25A3%25E1%2586%25BA%25202025-10-29%2520%25E1%2584%258B%25E1%2585%25A9%25E1%2584%2592%25E1%2585%25AE%25205.48.48.png%3Falt%3Dmedia%26token%3D72b48e33-3189-4ebd-83f1-3ff7ab96c2ab&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=272844a5&#x26;sv=2" alt=""><figcaption></figcaption></figure>

***

**④ Swap Fee Info Section**

This section activates automatically after you select both the _Sell Token_ and _Buy Token_. As you enter token amounts, all related values are dynamically updated.

Below the Swap Button, you’ll see a **summary line** showing the key exchange information. Clicking it expands the view to display detailed data, including:

* Exchange Rate
* Max Slippage (applied value)
* Price Impact
* Swap Fee

If the **Price Impact exceeds 5%**, a **warning message** appears in this section to alert you before proceeding.
