[Back](https://github.com/haslo/space4x/blob/master/readme.md)

# :rocket: Ship Customizations

## Customization Procedure

All ships of a type always have the same components.

* As long as no ships are built (or all are scuttled), pay component blueprint cost only for adding to ship
* If ships are built, pay component blueprint cost plus upgrade cost (per ship, round up)
* Whenever a new ship of the type is built, pay build cost of components as well as ship's build cost (tracker on board for cost)

## Customizable Types

* Trade Ship

  ```
  ┌─┬─┬─┐
  ├─┼─┼─┤
  └─┴─┴─┘
  ```

* Flagship

  ```
    ┌─┬─┐
    ├─┼─┤
  ┌─┼─┼─┼─┐
  └─┴─┴─┴─┘
  ```

* Scouts

  ```
  ┌─┐
  ├─┤
  └─┘
  ```

* Cruisers

  ```
    ┌─┐
    ├─┤
  ┌─┼─┼─┐
  └─┴─┴─┘
  ```

* Dreadnoughts

  ```
      ┌─┬─┐
  ┌─┐ ├─┼─┤ ┌─┐
  ├─┼─┼─┼─┼─┼─┤
  └─┴─┴─┴─┴─┴─┘
  ```

* Ground Bases

  ```
  ┌─┐
  ├─┤
  └─┘
  ```

* Orbital Stations

  ```
    ┌─┐
  ┌─┼─┼─┐
  ├─┼─┼─┤
  └─┼─┼─┘
    └─┘
  ```


## Customizations

* Cargo Hold

  ```
  ┌─┐
  └─┘
  ```

  | Level | Blueprint Cost | Upgrade Cost | Building Cost |
  |---|---|---|---|
  | - | 0 | 0.5 | 1 |

* Smuggling Hold

  ```
  ┌─┐
  └─┘
  ```

  | Level | Blueprint Cost | Upgrade Cost | Building Cost |
  |---|---|---|---|
  | - | 4 | 1 | 2 |

* Drives (can only be built in back)
  * Level 1-4

    ```
    ┌─┐ ┌─┬─┐ ┌─┬─┬─┐ ┌─┬─┐
    └─┘ └─┴─┘ └─┴─┴─┘ └─┴─┘
    ```

    | Level | Blueprint Cost | Upgrade Cost | Building Cost |
    |---|---|---|---|
    | 1 | 0 | 0 | 1 |
    | 2 | 0 | 0.5 | 1 |
    | 3 | 0 | 1 | 1 |
    | 4 | 1 | 1 | 2 |

  * Hyperspace

    ```
    ┌─┐
    └─┘
    ```

    | Level | Blueprint Cost | Upgrade Cost | Building Cost |
    |---|---|---|---|
    | - | 1 | 1 | 2 |

* Weapon Systems
  * Phaser 1-4 (can only be built in front)

    ```
            ┌─┐
    ┌─┐ ┌─┐ ├─┤ ┌─┐
    ├─┤ ├─┤ ├─┤ ├─┤
    └─┘ └─┘ └─┘ └─┘
    ```

    | Level | Blueprint Cost | Upgrade Cost | Building Cost |
    |---|---|---|---|
    | 1 | 0 | 0 | 1 |
    | 2 | 0 | 0.5 | 1 |
    | 3 | 0 | 0.5 | 1 |
    | 4 | 1 | 1 | 2 |

  * Photon Torpedoes 1-3

    ```
    ┌─┐ ┌─┐
    ├─┤ ├─┤ ┌─┐
    └─┘ └─┘ └─┘
    ```

    | Level | Blueprint Cost | Upgrade Cost | Building Cost |
    |---|---|---|---|
    | 1 | 0 | 0.5 | 1 |
    | 2 | 0 | 0.5 | 1 |
    | 3 | 1 | 1 | 2 |

* Shield Generators
  * Level 1-3

    ```
    ┌─┬─┐ ┌─┬─┬─┐ ┌─┬─┐
    └─┴─┘ └─┴─┴─┘ └─┴─┘
    ```

* Systems
  * Minor Systems

      ```
      ┌─┐
      └─┘
      ```

    * Tactical Computer 1-2

      | Level | Blueprint Cost | Upgrade Cost | Building Cost |
      |---|---|---|---|
      | 1 | 0 | 0.5 | 1 |
      | 2 | 1 | 0.5 | 2 |


    * Tractor Beam

      | Level | Blueprint Cost | Upgrade Cost | Building Cost |
      |---|---|---|---|
      | - | 3 | 0.5 | 2 |

    * Long-Range Sensors

      | Level | Blueprint Cost | Upgrade Cost | Building Cost |
      |---|---|---|---|
      | - | 3 | 0.5 | 1 |

  * Major Systems

      ```
      ┌─┐
      ├─┤
      └─┘
      ```

    * Tactical Computer 3

      | Level | Blueprint Cost | Upgrade Cost | Building Cost |
      |---|---|---|---|
      | 3 | 1 | 1 | 3 |

    * Shield Projectors

      | Level | Blueprint Cost | Upgrade Cost | Building Cost |
      |---|---|---|---|
      | - | 3 | 1 | 2 |

    * Carpet Bombs

      | Level | Blueprint Cost | Upgrade Cost | Building Cost |
      |---|---|---|---|
      | - | 3 | 1 | 2 |
