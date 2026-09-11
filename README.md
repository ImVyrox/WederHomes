# WederHomes

**Modern, Intuitive & Interactive Home System**

[![SpigotMC Resource](https://img.shields.io/badge/SpigotMC-138381-orange?style=flat&logo=spigotmc)](https://www.spigotmc.org/resources/wederhomes.138381/)

WederHomes is a modern, lightweight, and fully configurable home management plugin designed for PaperMC, Spigot, and Purpur servers. It features an interactive GUI menu with beds, particle visual effects, real-time action bar countdowns, and full HEX color support to provide a polished teleportation experience.

**Official Resource Page:** [SpigotMC - WederHomes](https://www.spigotmc.org/resources/wederhomes.138381/)

---

## Key Features

* **Paginated GUI Menu:** Interactive bed-based menu for effortless home teleportation, creation, and management.
* **Teleport Warmup & Particles:** Smooth countdown with particle visual effects and automatic cancellation on player movement.
* **Action Bar Countdown:** Displays real-time timers directly above the action bar.
* **Hexadecimal Color Support:** Full #RRGGBB color customization in titles, GUIs, and messages.
* **100% Configurable:** Customize every single message via lenguaje.yml.
* **Per-Group Home Limits:** Configure flexible home limits based on player ranks and permissions.
* **Admin Management Tools:** Inspect and manage any player's homes directly.

---

## Commands & Permissions

| Command | Description | Permission |
| :--- | :--- | :--- |
| `/homes` or `/home` | Opens the interactive GUI menu | `wederhomes.command.homes` |
| `/sethome <name>` | Sets a new home location | `wederhomes.command.homes` |
| `/delhome <name>` | Deletes an existing home | `wederhomes.command.homes` |
| `/wederhomes reload` | Reloads plugin configuration | `wederhomes.admin` |
| `/wederhomes admin <player>` | Opens another player's home menu | `wederhomes.admin` |

---

## Installation

1. Download `WederHomes.jar` from [SpigotMC](https://www.spigotmc.org/resources/wederhomes.138381/).
2. Place the `.jar` file into your server's `/plugins` directory.
3. Restart your server to generate configuration files.
4. Configure `config.yml` and `lenguaje.yml` according to your server preferences.

---

## Requirements

* **Server Software:** Paper, Purpur, Spigot, or any Paper fork (1.20+)
* **Java Version:** Java 21+
