[Back](https://github.com/haslo/space4x/blob/master/readme.md)

# :construction: Construction

## Materials

### Naturally Ocurring

* Rocks
* Metals
* Semiconductors
* Vespene Gas

### Composites

* Space-Grade Alloys (Metals, Vespene Gas)
* Electronics (Metals, Semiconductors)
* Reinforced Concrete (Rocks, Metals)

### Factory Types

* Extractor (all natural resources)
* Composer (all composites)

## Building / Transporting

* own factories, every step (extraction / composition) costs 1
  * track number of activations
  * when max is reached no more activations are possible (by any player), is reset at end of round only
  * thus see :cyclone: [Round Structure](https://github.com/haslo/space4x/blob/master/round_structure.md)
* own transports / smuggling routes are free
  * track number of activations for any trade ship
  * trade ship can be used as many times as it has cargo holds (2x with Improved Cargo Holds)
  * when max is reached no more activations are possible (by any player), is reset at end of round only
  * smuggling routes only usable by owner, work like transport routes otherwise (Improved Cargo Holds irrelevant)
* foreign factories, every step (extraction / composition) costs 2, 1 of which goes to owner
  * track number of activations, see above
  * factories only usable when both players agree or smuggling route is used
* foreign transports cost 1 (per involved player in route, not per ship), goes to owner
  * track number of activations, see above
  * transports only usable when both players agree
* Trade Posts provide all naturally occurring materials for 3 (vs. 2 for trader player, 1 for selfmade), composites for 10 (vs. 7 for trader player, 3 for selfmade)
* Every time a player buys from another player, give IOU token, see :moneybag: [Trade](https://github.com/haslo/space4x/blob/master/trade.md)

## Material Usage

### Military

| Name | Construction Site | Cost | Required Materials | Fallback Materials (5x) |
|---|---|---|---|---|
| Flagship | Shipyard | ? | Space-Grade Alloys, Electronics | - |
| Scout | Planet or Shipyard | ? | Space-Grade Alloys | Metals |
| Cruiser | Shipyard | ? | Space-Grade Alloys | - |
| Dreadnought | Shipyard | ? | Space-Grade Alloys, Electronics | - |
| Ground Base | Planet | ? | Reinforced Concrete | - |
| Orbital Station | Planet | ? | Space-Grade Alloys, Electronics | - |
| Shipyard | Planet or Construction Station | ? | Space-Grade Alloys, Electronics | - |
| Ground Troops | Ground Base | ? | - |

### Diplomacy

| Name | Construction Site | Cost | Required Materials | Fallback Materials (5x) |
|---|---|---|---|---|
| Embassy | Planet | ? | Rocks | - |
| Secret Agent | Embassy, Government Building | ? | - | - |
| Counter Espionage Agent | Embassy, Government Building | ? | - | - |
| Cultural Site | Planet | ? | - | - |
| Government Building | Planet | ? | Rocks, Metals | - |
| Broadcast Network | Planet or Construction Station | ? | Rocks, Electronics | - |

* Spies only cost credits for training
* Cultural Site can be anything from an underground cult to a historical monument, thus costs only credits

### Economics

| Name | Construction Site | Cost | Required Materials | Fallback Materials (5x) |
|---|---|---|---|---|
| Factory | Planet | ? | Rocks, Metals | - |
| Trade Ship | Trading Post or Shipyard | ? | Space-Grade Alloys | Metals |
| Trading Post | Planet or Construction Station | ? | Rocks | - |
| Wormhole Gate | Planet or Construction Station | ? | Electronics | - |
| Colony Outpost | Planet | ? | Rocks | - |
| Construction Station | - | ? | Space-Grade Alloys, Electronics | - |
| Construction Team | Planet or Construction Station | ? | - | - |

### Science

| Name | Construction Site | Cost | Required Materials | Fallback Materials (5x) |
|---|---|---|---|---|
| Research Facility | Planet | ? | Electronics | Rocks |
| Research Space Station | Planet or Construction Station | ? | Space-Grade Alloys | - |
| Terraforming Station | Barren Planet | ? | Rocks, Vespene Gas | - |
