# 👥 User Commands

## User Commands Documentation

***

### `/user hunt`

Start or change your **SHADOW** Pokémon hunt by specifying the Pokémon you wish to hunt.

**Usage:** `/user hunt <pokemon>`

* `<pokemon>`: The name of the Pokémon you wish to hunt.

**Examples:**

* `/user hunt pikachu` - Begins a hunt for Pikachu.
* `/user hunt charizard` - Switches your hunt to Charizard.

If you try to hunt a Pokémon that is not in the valid list, you will receive an error message. If you haven't started your Pokémon journey, you will be prompted to do so. As you collect Pokémon with that name, your chances of getting a shadow of said Pokémon go up, at around 6,000 would be 100% chance on next Pokémon with the name specified.&#x20;

***

### `/user region`

Set your region in the game, which affects your Pokémon's regional evolutions.

**Usage:** `/user region <region>`

* `<region>`: The region you want to set. Valid options are `original`, `alola`, `galar`, `hisui`, and `paldea`.

**Examples:**

* `/user region alola` - Sets your region to Alola.
* `/user region galar` - Sets your region to Galar.

If you specify an invalid region, you will receive an error message.

***

### `/user bal`

Displays your in-game balances, such as credits, redeems, EV points, upvote points, and your selected fishing rod.

**Usage:** `/user bal [user] [hidden]`

* `[user]`: (Optional) Specify another user to view their balances. Defaults to yourself if not specified.
* `[hidden]`: (Optional) If set to true, the balance will only be visible to you. Defaults to false.

**Examples:**

* `/user bal` - Shows your own balances.
* `/user bal @username` - Shows the balances of the mentioned user.
* `/user bal hidden:true` - Shows your balances only to you.

If the user has not started playing, an error message will be displayed. Also, if the user's balances are not visible to others and you try to check them, you will receive a permission error.

***

### `/user bag`

Lists all the items in your bag.

**Usage:** `/user bag [hidden]`

* `[hidden]`: (Optional) If set to true, the item list will only be visible to you. Defaults to true.

**Examples:**

* `/user bag` - Displays a list of your items, visible only to you.

If you haven't started your journey, you will be prompted to do so.

***

### `/user trainernick`

Sets your trainer nickname for use in global leaderboards and other public-facing features.

**CAN ONLY BE SET ONCE, CHOOSE WISELY**

**Usage:** `/user trainernick <name>`

* `<name>`: The trainer nickname you want to set.

**Examples:**

* `/user trainernick AshKetchum` - Sets your trainer nickname to AshKetchum.

There are restrictions on the nickname:

* It cannot contain `@here`, `@everyone`, or `http` to prevent abuse.
* It must be no longer than 18 characters.
* It cannot contain Unicode characters or the pipe character `|`.

If you already have a set nickname or the chosen nickname is taken, you will be informed accordingly.
