[Back](https://github.com/haslo/space4x/blob/master/readme.md)

# :moneybag: Trade

## Player Deals

Players can strike any kind of deal at any time. Negotiations should be open before the other players in the interest of game speed. Players that have ships or planets in neighbouring hexes or have shared hexes can exchange credits and IOU Tokens as part of their deals. Every part of a deal that is agreed to be made immediately is binding. Any part of a deal that applies to promises of things that happen / don't happen in the future is not binding.

## Production and Transport

### Trade Ships (Movement / Emplacement)

Trade Ships can move from hex to hex like any other unit. Additionally, they can also move from a hex to any of the edges of that hex (this is called Emplacement). As long as they are emplaced on a hex edge, they faciliate trade through that hex edge.

### Costs of Production

* own factories, every step (extraction / composition) costs 1
  * track number of activations
  * when max is reached no more activations are possible (by any player), is reset at end of round only
  * thus see :cyclone: [Round Structure](https://github.com/haslo/space4x/blob/master/round_structure.md)
* own transports / smuggling routes are free
  * track number of activations for any trade ship
  * trade ship can be used as many times as it has cargo holds (2x with Improved Cargo Holds)
  * when max is reached no more activations are possible (by any player), is reset at end of round only
  * smuggling routes only usable by owner, work like transport routes otherwise (Improved Cargo Holds irrelevant)
* own Trade Posts provide all naturally occurring materials for 3 (vs. 2 for trader player, 1 for selfmade), composites for 6 (vs. 4 for trader player, 3 for selfmade)
* foreign factories, every step (extraction / composition) costs 1, which goes to owner
  * track number of activations, see above
  * factories only usable when both players agree or smuggling route is used
* foreign transports cost 1 (per involved player in route, not per ship), which goes to owner
  * track number of activations, see above
  * transports only usable when both players agree
* foreign Trade Posts provide all naturally occurring materials for 3, with 1 going to the player, composites for 6, with 2 going to the player

### Selling Goods

All unsold goods can be sold to a Trade Station at the end of the round (only from own factories). Production and transporting costs as for production, sale prices equal to buy prices.

* Example: composite good can be sold for 6, costs 3 to produce => 3 profit.
* Example: naturally occurring good can be sold for 3, costs 1 to produce, needs to be transported because Trade Post is far away (1 goes to transporting player) => 1 profit

## Player Interactions

### Trading partners and consent

* All factories want to maximize profits and will sell to all interested parties, always
* Trading ships:
  * The owner of the trading ship has to agree on the transport
  * Cargo Holds will only transport goods away from planets that allow it
    * after that, an uninterrupted line of trade ships must be drawn
    * other planets have no impact on the trade ships in their hex (unless they're Stratocracy, where hexes along the way can deny the route if they wish to do so)
  * Smuggling Holds can be used to transport any goods
  * The only way to stop smuggling is an established Stratocracy
* Trade posts attract traders from all over the universe; hey are always interested in trading with all players

### IOU Token

* Each player starts with 5? 10? IOU tokens
* Every time a player buys from or trades through another player, the seller / trader can pass an IOU token to the buyer, if they have any remaining
* When a player attacks an opponent that they have IOU tokens of, all IOU tokens are returned and 2 VPs are deducted from the attacking player per token

### Secret Agents and Counter Espionage Agents
