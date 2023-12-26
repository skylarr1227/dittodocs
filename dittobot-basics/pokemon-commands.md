---
description: Pokémon informational commands
---

# 🦧 Pokémon Commands

## Pokemon Commands Documentation

### `/poke moveset`

Shows a list of all moves that your currently selected Pokémon can learn.

**Usage:** `/poke moveset`

**Example:**

* `/poke moveset`

If the selected Pokémon is an Egg or cannot learn any moves, you'll be notified accordingly.

***

### `/poke learn_all`

Teaches your selected Pokémon four moves at once.

**Usage:** `/poke learn_all <first> <second> <third> <fourth>`

* `<first>`: First move you want the Pokémon to learn.
* `<second>`: Second move you want the Pokémon to learn.
* `<third>`: Third move you want the Pokémon to learn.
* `<fourth>`: Fourth move you want the Pokémon to learn.

**Examples:**

* `/poke learn_all tackle growl tail whip quick attack`
* `/poke learn_all ember leer smokescreen flame wheel`

**Note:** The moves must be learnable by the selected Pokémon. If the move is not learnable, you will be prompted to try again.

***

### `/poke learn`

Teaches your selected Pokémon a new move in a specified slot.

**Usage:** `/poke learn <slot> <move>`

* `<slot>`: The move slot number (1, 2, 3, or 4) where you want the new move to be learned.
* `<move>`: The move you want the Pokémon to learn.

**Examples:**

* `/poke learn one tackle`
* `/poke learn two thunderbolt`

**Note:** If the Pokémon cannot learn the specified move, you'll receive an error message.

***

### `/poke moves`

Displays the moves your currently selected Pokémon has learned.

**Usage:** `/poke moves`

**Example:**

* `/poke moves`

This command will show an embed with the current moves in slots 1 to 4.

***

### `/poke addevs`

Adds effort value points (EVs) to one of the stats of your selected Pokémon.

**Usage:** `/poke addevs <amount> <stat>`

* `<amount>`: The number of EV points to allocate. Cannot exceed 252 for a single stat.
* `<stat>`: The stat to which you want to add EV points. Valid stats are `attack`, `hp`, `defense`, `special attack`, `special defense`, and `speed`.

**Examples:**

* `/poke addevs 252 speed` - Adds 252 EV points to Speed.
* `/poke addevs 64 attack` - Adds 64 EV points to Attack.

**Note:** You must have enough EV points available to add to the Pokémon. If you try to add more than the maximum allowed EVs to a stat or the total EVs exceed 510, you will receive an error message.
