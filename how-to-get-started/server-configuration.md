---
description: Guide to setting up your server with DittoBOT (Server Owners/Admins)
---

# ⚙ Server Configuration

### Pokémon Spawns:

By default, all channels are set to **DISABLED**. This means that when DittoBOT is invited to your server, it will not spawn Pokémon or send any spam messages anywhere. To **ENABLE** these features, you must specify a spawn channel with the command detailed below.

&#x20;**Server Commands:**

<details>

<summary>Server/Guild Configuration</summary>

* `/settings server auto_delete`\
  \- Toggle ON/OFF auto-deletion of the spawn image when a Pokémon is caught. (default OFF)
* `/settings server auto_pin`\
  \- Toggle ON/OFF automatic pinning of rare spawns. (default OFF)
* `/settings server silenceserver`\
  \- Toggle level up messages ON/OFF for the entire guild. (manage\_messages)

</details>

<details>

<summary>Spawn Configuration</summary>

1. `/settings spawns enable`\
   \- Enable spawns in a channel
2. `/settings spawns enable_all`\
   \- Enable spawns in all channels (over-rides disabled channels)
3. `/settings spawns disable`\
   \- Disable spawns for a channel
4. `/settings spawns disable_all`\
   \- Disable spawns in all channels (over-rides enabled channels)
5. `/settings spawns small`\
   \- Toggle ON/OFF small spawn messages (default OFF)
6. `/settings spawns reset`\
   \- Reset all spawn channels and redirects, to default settings
7. `/settings spawns config`\
   \- Show current server channel configuration&#x20;



</details>

<details>

<summary>Spawn Redirect Configuration</summary>

/`settings redirect add`\
`-`Set a channel as a spawn redirection

`/settings redirect remove`\
\- Remove a channel as a spawn redirection

</details>





