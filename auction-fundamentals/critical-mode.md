# Critical Mode

So far, we've explored the most basic mode of auction our platform will support. Our all-pay nature can grow an auction prize from 100 USDT to well over 100K USDT in just 500 bids, with the next highest bid costing 501 USDT - not a bad return on investment for the bidder if they win.

**Critical Mode** takes our concept further, and is one of two 'gamified' auction modes we strongly recommend to auction creators.&#x20;

In **Critical Mode**, the auction creator chooses a **Critical Mode Threshold (a number of seconds)** along with an action defined below.&#x20;

**Critical Mode** begins when time remaining to the auction end time reaches the **Critical Mode Threshold.** Once active, one of the below actions is taken on every bid placed:

* **Extend the auction by X seconds**\
  ****This action adds a given number of seconds to the auction end time after each critical mode bid is placed, extending the time for others to place competing bids.
* **Restart the Critical Mode Countdown**\
  When critical mode threshold begins, a new countdown timer starts. With this action chosen by the auction creator, the timer is restarted.

{% hint style="info" %}
**Example:** Our example auction has been running for 6 days 23 hours 55 minutes, and had an end time set to 7 days from creation. We also set a **Critical Mode Threshold** of 300 seconds, which has now been reached. We have received 500 bids so far!

\
As we opted to restart the Critical Mode Countdown, user **JianYang's bid of 501 USDT -** received with 3 minutes 32 seconds until the auction ends restarts the critical mode countdown clock to 5 minutes.\


With 20 seconds to go, **ErlichBachmann** bids 502 USDT - the timer goes back to 5 minutes. \
\
A rich user interface creates a tense and enthralling atmosphere for bidders and observers alike, with a graph showing bids received and a millisecond countdown clock present.
{% endhint %}
