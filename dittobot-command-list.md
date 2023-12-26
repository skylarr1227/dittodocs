# DittoBOT Command List

### Getting Started!

***



{% tabs %}
{% tab title="Starting" %}
`/start dittobot <code>`\
\- Use this command to start your journey. The majority of bot functions require starting first.

* This will open a menu with 3 buttons, one for each starter type to choose from, after choosing, you will select[ ](#user-content-fn-1)[^1]from the dropdown which starter you want. \
  Welcome to to DittoBOT, we hope you enjoy what we've created!\

* `<code>` is an optional field which can provide different starting conditions than normal. In the future, this will also be used for "invite" codes for users to invite their friends.
{% endtab %}

{% tab title="Viewing Your Pokémon" %}
### Filter Commands

***

### `/f p [args=""]`



**Description:**\
Filter your Pokémon list based on various criteria. If no arguments are provided, the default filter of "male | !male" is used to ensure you get an output.

**Examples:**

* `/f p legendary & shiny` Filters and shows only your Pokémon that are both legendary and shiny.
* `/f p type water | type fire` Filters and shows your Pokémon that are either water type or fire type.
* `/f p level > 50 & !shiny` Filters and shows your Pokémon that are above level 50 and are not shiny.

***

### `/f m [args=""]`

**Description:**\
Show a filtered list of Pokémon available on the global market for sale.

**Examples:**

* `/f m price < 10000` Filters the market listings for Pokémon with a price less than 10,000.
* `/f m iv > 80` Filters the market listings for Pokémon with IVs greater than 80%.

***

### `/f e [args=""]`

**Description:**\
Show a filtered list of eggs you have bred.

**Examples:**

* `/f e type dragon` Filters and shows all dragon type eggs.
* `/f e shiny` Filters and shows all shiny eggs.

***

### `/external send_html [filter_type]`

**Description:**\
Generates an HTML file with a list of Pokémon based on the specified filter and sends it via a clickable link.

**Examples:**

* `/external send_html "legendary"` Generates and sends a link to an HTML list of all legendary Pokémon.
* `/external send_html "shiny"` Generates and sends a link to an HTML list of all shiny Pokémon.

***

### `/getids [msg_id]`

**Description:**\
A utility command for retrieving a list of IDs from a filter list message using the message ID.

**Examples:**

* `/getids 123456789012345678` Retrieves and displays the list of Pokémon IDs from the message with the given ID.

***

## Notes

* Arguments for filters can be combined using **logical operators `&` (AND), `|` (OR), and `!` (NOT).**
* Use parentheses `()` to **group conditions** and **control the order of operations.**
* IV filters can be **combined with comparative operators like `>`, `<`, and `=`.**
* Some filters like `level`, `price`, `iv`, and `ev` can also **sort the result in ascending (`asc`) or descending (`desc`) order** if mentioned as the only argument.

***

This guide is designed to prove an easy-to-navigate and user-friendly experience. The examples provided are not exhaustive, so don't hesitate to experiment with different combinations to suit your needs. Enjoy using DittoBOT for all your Pokémon filtering needs!&#x20;
{% endtab %}
{% endtabs %}





### /tutorial

#### View a tutorial to get you started with DittoBOT.

## Breeding

### /breed

Breed two Pokémon. pokes - The Pokémon numbers of the two Pokémon to breed, separated by a space.

### /breedswith \[filter\_args]

Filter your pokemon to show only ones that can breed with the provided pokemon. poke - The pokemon that will be used to check compatibility. filter\_args - Extra arguments to filter with. See ## /filter for more information.

### /mothers

View the breeding cooldown for your mother pokemon.

### /daycare

View your unhatched eggs.

## Chests

### /open common

Open a radiant chest.

### /open rare

Open a radiant chest.

### /open mythic

Open a radiant chest.

### /open legend

Open a radiant chest.

### /radiant \[pack]

Spend your radiant gems. pack - The pack number to buy. Do not pass this arg to view the packs.

## Dueling

### /duel single

Engage in a pokemon duel. user - The user to duel.

### /duel party

Engage in a pokemon duel. user - The user to duel.

### /duel npc

Engage in a pokemon duel.

## Pokemon Setup

### /select

Select a pokemon. poke - The pokemon number to select, or "new".

### /add evs

Add evs to your select pokemon. amount - The amount of ev points to add. stat - The stat to add ev points to.

### /change nature

Change the nature of your selected pokemon. nature - The nature to make your selected pokemon.

### /learn

Teach your selected pokemon a move. slot - The move slot to learn this move in. move - The move to learn.

### /moves

View the moves of your selected pokemon.

### /moveset

View the learnable moves of your selected pokemon.

### /nick \[nick]

Change your pokemon's nickname. nick - The nickname to set it as. Leave blank to clear.

### /unequip

Unequip the held item from your selected pokemon.

### /equip

Equip a held item on your selected pokemon. item - The item to equip.

### /apply

Apply an item to your selected pokemon. item - The item to apply.

## Personal (trainer info)

### /stats

Show some stats about yourself.

### /trainer \[user]

Show your trainer card, or the trainer card of another member. user - The user who's card will be shown. Leave blank to show your card.

### /trainernick

Change your trainer nickname, which is shown on pokemon you catch. nick - The nickname to set it as.

### /bal \[user]

Show your balance, or the balance of another member. user - The user who's balance will be shown. Leave blank to show your balance.

## Activities

### /fish

Fish for some pokemon.

## Evolution

### /lunarize

Lunarizes the selected Necrozma into Necrozma-dawn form. lunala - The lunala to fuse with.

### /solarize

Solarizes the selected Necrozma into Necrozma-dusk form. solgaleo - The solgaleo to fuse with.

### /fuse

Fuses the selected Kyurem or Calyrex to change its form. form - The form to make this poke. poke - The poke to fuse with.

### /deform

Deforms your selected pokemon.

### /form

Forms your selected pokemon. form - The form to form into.

### /mega evolve

Mega evolve your selected pokemon.

### /mega devolve

Mega evolve your selected pokemon.

### /mega x

Mega evolve your selected pokemon.

### /mega y

Mega evolve your selected pokemon.

### /drop

Drop your selected pokemon's equipped item.

### /transfer

Transfer your selected pokemon's equipped item to another pokemon. poke - The pokemon number to transfer the item to

### /cash out

Convert your coins to credits. amount - The amount of coins to convert.

## Market

### /m add

Interact with the market. poke - The pokemon to add to the market. price - The price to list the pokemon for.

### /m buy \<listing\_id>

Interact with the market. listing\_id - The ID of the listing you want to buy.

### /m remove \<listing\_id>

Interact with the market. listing\_id - The ID of the listing you want to remove.

### /m i \<listing\_id>

Interact with the market. listing\_id - The ID of the listing you want to view.

## Donations

### /donate

Make a donation to the bot and get some redeems.

## Missions

### /mission list

View today's missions.

### /mission claim

View today's missions.

## Party

### /party view

Manage your party.

### /party add \[poke]

Manage your party. slot - The party slot to add the pokemon in. poke - The pokemon you want to add. Leave blank to add your selected pokemon.

### /party remove

Manage your party. slot - The party slot to remove the pokemon from.

### /party register

Manage your party. name - The name to register your party under.

### /party deregister

Manage your party. name - The name of the party to deregister.

### /party load

Manage your party. name - The name of the party to load.

### /party list

Manage your party.

## Pokedex

### /pokedex national

View your pokedex.

### /pokedex unowned

View your pokedex.

## Misc

### /spread honey

Spread honey in your server to attract rare pokemon.

### /server

View stats abour your server.

### /release

Release a pokemon. poke - The pokemon number to release, or "new".

### /leaderboard

View various leaderboards for DittoBOT. board - The leaderboard to view.

### /region

Change your region to make your pokes evolve into regional forms. region - The region to enter.

### /visible

Toggle allowing others to view your ## /bal.

### /updates

View recent updates to the bot.

### /silence

Toggle silencing level up messages for your pokemon.

### /status

View some statistics about DittoBOT.

### /claim

Claim rewards in exchange for 5 upvote points.

### /ping

Pong!.

### /vote

Upvote the bot and get upvote points.

### /predeem

Claim redeems for being a patreon.

### /invite

Invite DittoBOT to your server.

## Official Server

### /nitro claim

Claim rewards for boosting the DittoBOT Official Server.

## Pokemon Listing

### /p

List your owned pokemon.

### /fav list

View your pokedex.

### /fav add \[poke]

View your pokedex. poke - The pokemon number to add. If not provided, your selected pokemon is used instead.

### /fav remove \[poke]

View your pokedex. poke - The pokemon number to remove. If not provided, your selected pokemon is used instead.

### /f m \[args]

Filter your pokemon. args - Arguments to filter with. For more information about this, see ## /tutorial.

### /f p \[args]

Filter your pokemon. args - Arguments to filter with. For more information about this, see ## /tutorial.

### /tags list

Add tags to your pokemon for easy filtering. poke - The pokemon number, or "new".

### /tags add

Add tags to your pokemon for easy filtering. tag - The tag to add. pokes - The pokemon number(s), or "new".

### /tags remove

Add tags to your pokemon for easy filtering. tag - The tag to remove. pokes - The pokemon number(s), or "new".

### /order ivs

Change the default order of your pokemon.

### /order default

Change the default order of your pokemon.

### /order evs

Change the default order of your pokemon.

### /order name

Change the default order of your pokemon.

### /order level

Change the default order of your pokemon.

## Info## /Viewing Pokemon

### /i \[poke]

View information on a pokemon. poke - The pokemon number, or "new". If not provided, your selected pokemon is used instead.

### /qi \[poke]

View information on a pokemon in a more compact format. poke - The pokemon number, or "new". If not provided, your selected pokemon is used instead.

### /lookup move

Lookup data on pokemon. move - The move to get data about.

### /lookup ability

Lookup data on pokemon. ability - The ability to get data about.

### /lookup type

Lookup data on pokemon. type - The type to get data about.

## Redeeming

### /packs

View the different redeemable packs.

### /redeem \[item]

Spend your redeems. item - What you want to buy with your redeems. Leave blank to see what you can buy.

### /redeemmultiple

Redeem multiple of the same item at once. amount - The number of the item to redeem. item - The item to redeem. Can be a pokemon name or "credits".

### /buy redeems \[amount]

Buy items. amount - The amount to buy. Leave blank to view how many you can buy this week.

## Server Configuration and Setup

### /auto delete

Have the bot automatically perform certain actions on spawns.

### /auto pin

Have the bot automatically perform certain actions on spawns.

### /redirect add \[channel]

Redirect spawns to specific channels. channel - The channel to add. If not provided, the current channel will be used.

### /redirect remove \[channel]

Redirect spawns to specific channels. channel - The channel to remove. If not provided, the current channel will be used.

### /redirect clear

Redirect spawns to specific channels.

### /commands disable \[channel]

Set whether commands can be used in a channel. channel - The channel to disable commands in. If not provided, the current channel will be used.

### /commands enable \[channel]

Set whether commands can be used in a channel. channel - The channel to enable commands in. If not provided, the current channel will be used.

### /spawns disable \[channel]

Set whether pokemon can spawn in a channel. channel - The channel to disable spawns in. If not provided, the current channel will be used.

### /spawns enable \[channel]

Set whether pokemon can spawn in a channel. channel - The channel to enable spawns in. If not provided, the current channel will be used.

### /spawns small

Set whether pokemon can spawn in a channel.

## Shop and items

### /shop \[shop]

View items in the shop. shop - The shop to view. Leave blank to view the shops.

### /buy item

Buy items. item - The item to buy.

### /buy daycare \[amount]

Buy items. amount - The number of spaces to buy. Defaults to 1.

### /buy coins

Buy items. amount - The number of coins to buy.

### /buy vitamins

Buy items. vitamin - The vitamin to buy. amount - The number of vitamins to buy.

### /buy candy \[amount]

Buy items. amount - The number of rare candies to buy. Defaults to 1.

### /buy chest \<credits\_or\_redeems>

Buy items. rarity - The chest rarity to buy. credits\_or\_redeems - Whether you want to spend credits or redeems.

### /bag

View the contents of your bag.

## Trading

### /gift

Gift some credits to another user. user - The user to give credits to. amount - The amount of credits to give.

### /give

Give a pokemon to another user. user - The user to give the pokemon to. poke - The pokemon to give.

### /trade

Start an interactive trade with another user. user - The user to trade with.

### /Trade

## Selling

### /sell item \[amount]

Sell different things. item - The name of the item you'd like to sell. amount - The amount you'd like to sell. Defaults to 1.

### /sell egg

Sell different things. num - The egg's number, or "new".

## Skins

### /skin apply

Manage your pokemon skins. poke - The pokemon number to add the skin to. skin - The name of the skin to apply.

### /skin list

Manage your pokemon skins.

### /skin preview

Manage your pokemon skins. poke - The pokemon name the skin is for. skin - The name of the skin to preview.

## Shadow Hunting

### /hunt

Select a pokemon to shadow hunt for, giving a chance to get a shadow skin for it. poke - The pokemon to hunt for.

## Seasonal

### /easter buy \[option]

Easter related commands. option - The option number you want to buy. Ommit this to see the list of choices, with prices.

### /easter list

Easter related commands.

### /easter convert \[egg]

Easter related commands. egg - The egg to convert into. Requires one of each egg from the tier below this egg's tier to convert.

[^1]: 
