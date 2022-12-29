# Battle Royale Mode

While Critical Mode is a great use of auction and game theory to add tension and drama to an auction, it does little to create a sense of urgency in placing a new bid to become the highest bidder. Therefore, we created **Battle Royale Mode.**

Just like **Critical Mode**, a threshold is set by the auction creator - a point in time at which **Battle Royale Mode** will activate. Upon activation, a percentage of previous bidders - from earliest to newest - are eliminated from the auction and lose the ability to place new bids.

Unlike Critical Mode, there is no reset for this timer. The only way to stay in the auction is to bid.

A rich user interface charts the progress of the elimination akin to Formula 1's knock-out qualifying rounds, with those at risk of elimination clearly indicated on screen.

{% hint style="info" %}
**Example:** Our example auction enters **Battle Royale Mode** with 5 minutes to go to the original end time. User **JianYang** is currently top bidder, with **ErlichBachmann, RichardHendricks322,  Gavin1Belson and MonicaHall99** the previous top bidders.

When creating our auction, we chose to eliminate 20% of bidders every minute. Let's see how this auction closes:

_With 5 minutes to go, the user interface updates to display **Battle Royale Mode** and shows a leaderboard of bidders. **MonicaHall99** is the bidder at risk of elimination._

_With 4 minutes 10 seconds to go, **MonicaHall99** places a bid. She becomes top bidder, and with just 10 seconds until elimination, **Gavin1Belson** becomes the bidder at risk._&#x20;

_**Gavin1Belson** is eliminated with 4 minutes to go. The countdown continues; the user interface updates to show that now **RichardHendricks322** is at risk of elimination._

_**RichardHendricks322** and **ErlichBachmann** are away from Aucry - the ruthless countdown continues and both are eliminated by the time there are 2 minutes to go._

_With just 1 minute 20 seconds to go, **JianYang** bids and retakes the lead in the auction. **MonicaHall99** bids with just 1 second before she is eliminated; **JianYang** is eliminated and **MonicaHall99** is the winner of the auction as the only remaining bidder left._

In our example, we have 5 bidders in total - however, each elimination round could potentially involve hundreds of bidders around the world.
{% endhint %}

