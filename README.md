# ❤️ BladeHearts Plugin (BETA) ❤️

Welcome to **BladeHearts**, a powerful and customizable Minecraft plugin that lets you grant players extra permanent (or dangerous 👀) hearts using enchanted items! This is the **BETA snapshot** — the world of hearts is expanding! 💉💖

---

## 🔥 Features
- 💖 `/bh give <player> <type> <amount>` command to grant special heart items
- 📂 `/bh reload` command to reload the config.yml file
- ⚔️ **Tab completer** support for easier command usage

---

## 🧠 Now With 6 Heart Types!

| Type         | Effect                                                                 |
|--------------|------------------------------------------------------------------------|
| ❤️ `standard`    | +1 permanent heart                                                  |
| 🎲 `suspicious`  | 50% chance to gain or lose 1 heart                                   |
| ✨ `blessed`      | +1 permanent heart + a random positive effect                        |
| 💀 `cursed`       | +1 permanent heart + a random negative effect                        |
| 💛 `golden`       | +4 temporary absorption hearts (5 minutes)                          |
| 🕸️ `wither`        | -1 permanent heart (just in case you’re feeling edgy)              |

Each item has ✨ custom name & lore support ✨ — now editable in `config.yml` with full **HEX formatting**! 💅

---

## 🧪 Command Usage

`/bh give <player> <type> <amount>` - permission: bh.give

- **player** – The target player
- **type** – The heart type (`standard`, `suspicious`, etc.)
- **amount** – Number of heart items to give

### Example:
/bh give wolnefury standard 3

This will give **3 enchanted red heart items** to player `wolnefury`.

`/bh reload` - permission: bh.reload

- Reloads the config.yml file

`/bh help` - permission: none, eveybody has access

Note that if a player doesn't have permission for `/bh give`, it won't be displayed for them on the help list.

## **Tab completer** is fully permission-based:
- Only shows you stuff you're allowed to use 🎯
- Doesn't suggest `/bh give` if you're not allowed to use it

---

## 🧪 Installation
1. Drag & drop the BladeHearts `.jar` into your server’s `plugins` folder
2. Restart or reload the server
3. Start giving hearts to your fav players 🥹💕

---

## 📊 Roadmap (Coming Soon)

- 🔊 Editable sound effects
- 🎨 Ability to change actual item used per heart
- 🧪 Fully custom hearts via config
- 🛡️ Permission-based restrictions per heart type

---

## ⚙️ Configuration

Located in `plugins/BladeHearts2/config.yml`:

- 🌈 Customizable messages with **HEX color support**
- ✍️ Editable item **names and lores** for every heart type
- 🧠 Set **min/max health**
- 🐛 `debug-mode: true/false` to log advanced actions for admins

---

## 🐞 Bugs & Ideas?
Open an issue or start a discussion here on GitHub! Let’s make BladeHearts legendary together 💬🔥

---

🖤 Made with love by **wolnefury**
