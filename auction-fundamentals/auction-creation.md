# Auction Creation

Aucry Auctions are based strongly upon the _'All-Pay Bidding Fee Auction'_ model, but with a major difference we believe makes our model unique.&#x20;

Our most basic auction format is created with an 'initial value', 'end time' and 'bid step'.&#x20;

The user creating the auction transfers the initial value to the **Aucry Hub** contract at the time of creation, which deploys a new **Aucry Auction** contract with the above specified settings. **Aucry Hub** then transfers the initial value to the auction.\
\
Bids are then invited from the public in multiples of this bid step until the end time is reached. The auction is for ownership of the **Aucry Auction** contract. The owner of the Aucry Auction contract is able to transfer the value of the contract to their wallet.

{% hint style="info" %}
**Example:** If an auction is created in USDT with a bid step of `1 USDT`, bids will be placed at `1 USDT, 2 USDT, 3 USDT, 4 USDT` and so on.
{% endhint %}
