# 🧊 LoafieChilly – Minecraft Server Setup



A fully configured Minecraft server setup including plugins, permissions, economy, skills, Slimefun, crossplay support, and quality-of-life enhancements.

> ⚠ This repository does NOT include world files or plugin `.jar` files.
> You must download the required plugins separately (listed below).

---

## 📦 Server Information

- **Platform:** Paper / Spigot
- **Version:** (minecraft server version 1.20.5)
- **Mode:** Survival / Economy / Skills
- **Crossplay:** Java + Bedrock supported

---

## 🔌 Required Plugins

Download the following plugins and place them in your `/plugins` folder:

- AdvancedEnchantments (v9.22.6)
- ajLeaderboards (v2.10.1)
- AuctionHouse (v1.13)
- AuraSkills (v2.3.10)
- Chunky (v1.4.40)
- CMI (v15.8.2)
- EssentialsX (v2.22.0-dev)
- EssentialsXChat (v2.22.0-dev)
- EssentialsXSpawn (v2.22.0-dev)
- FancyHolograms (v2.9.0)
- floodgate-spigot
- Geyser-Spigot
- GSit (v1.3.11)
- Jobs (v5.2.6)
- LevelledMobs (v4.4.0 b137)
- LuckPerms-Bukkit (v5.5.2)
- PlaceholderAPI (v2.11.7)
- SkinsRestorer
- Slimefun4 (Dev build)
- TAB (v5.4.0)
- Vault
- ViaVersion (v5.7.0)

---

## 🌐 Crossplay Support

This server supports Bedrock players using:

- **Geyser**
- **Floodgate**

Make sure to properly configure Geyser for your server environment.

---

## 🔁 Version Compatibility

- **ViaVersion** allows newer Minecraft clients to join older server versions.
- Ensure compatibility between your Paper version and plugin versions.

---

## 🛠 Setup Instructions

1. Install Paper or Spigot.
2. Start the server once to generate files.
3. Stop the server.
4. Download all required plugins.
5. Place plugins inside `/plugins`.
6. Copy this repository's configuration files into your server directory.
7. Start the server.

---

## 📁 What Is Included in This Repository

✔ Plugin configuration files  
✔ Server configuration files (`server.properties`, `.yml`, etc.)  
✔ Permission setup (LuckPerms ready)  
✔ Economy & skills configuration  

---

## ❌ What Is NOT Included

✖ World files  
✖ Plugin `.jar` files  
✖ Logs  
✖ Libraries  

These are excluded to keep the repository clean and within GitHub size limits.

---

## 🔐 Permissions

This setup uses **LuckPerms**.

After installation:

```bash
/lp editor
```

Configure groups as needed.

---

## 💰 Economy System

Economy is powered by:

- CMI
- Vault
- Jobs
- AuctionHouse

Ensure Vault loads properly before other economy plugins.

---

## 🧪 Development Notes

- Slimefun4 uses a development build — ensure compatibility with your server version.
- Always test plugin updates on a staging server before applying to production.

---

## 📜 License

This configuration is provided as-is.  
You are responsible for complying with each plugin’s individual license.

---

## 👑 Credits

Server configuration by LoafieChilly.
Plugins belong to their respective developers.
