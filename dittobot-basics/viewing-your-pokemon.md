# 👀 Viewing your Pokémon

***

## Filter Commands

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
