# 🌊 Bedrock-Java-Bridge — Join Guide

A Fabric-based Minecraft server with cross-play support via Geyser, so both **Java** and **Bedrock** players can join together.

- **Minecraft Version:** 26.2
- **Loader:** Fabric
- **Java Port:** `25565`
- **Bedrock Port:** `19132` (UDP)
- **Server Address:** `192.168.1.166`

---

## 📥 Download (Java Edition players)

Java players need the client-side mod pack to match the server's mods.

**[⬇️ Download the mod pack (.zip)](PASTE_YOUR_DOWNLOAD_LINK_HERE)**

### Installing the mod pack

1. Install [CurseForge](https://www.curseforge.com/download) if you haven't already.
2. Download the zip from the link above.
3. Open CurseForge and click **Import Zip**.
4. Run the instance.

---

## 🎮 How to Join (Java Edition)

1. Open CurseForge and run the **Bedrock Bridge** instance.
2. Go to **Multiplayer** → **Add Server**.
3. Enter:
   - **Server Name:** anything you like
   - **Server Address:** `192.168.1.166:25565`
4. Click **Done**, then double-click the server to connect.

---

## 🕹️ How to Join (Bedrock Edition — Mobile & Windows)

No mods needed — just connect directly. This works out of the box on **iOS, Android, and Windows 10/11**.

1. Open Minecraft.
2. Go to **Play** → **Servers** tab → **Add Server**.
3. Enter:
   - **Server Name:** anything you like
   - **Server Address:** `192.168.1.166`
   - **Port:** `19132`
4. Save, then tap the server to connect.

> **Heads up:** Bedrock players connect through a Java account link the first time they join (via Geyser). You'll be prompted with a code/link to connect your Microsoft account to a Java account when you first attempt to join.

If you can't find **Add Server**, follow [this tutorial](https://youtu.be/7rgg-R7DPy4).

---

## 🎮 How to Join (Bedrock Edition — Xbox, PlayStation, Switch)

Consoles don't have an "Add Server" option built in — Mojang only exposes their own curated Featured Servers list on these platforms. To connect to a custom server like ours, you'll need **BedrockConnect**, a free community tool that adds a server-list screen you can use to type in our IP.

### Setup (DNS method — no download required)

1. Go into your console's **network/internet settings** and set a **manual DNS**:
   - **Xbox / Nintendo Switch:** Primary DNS `104.238.130.180`, Secondary DNS `8.8.8.8`
   - **PlayStation:** Primary DNS `45.55.68.52`, Secondary DNS `8.8.8.8`
2. Save and reconnect to your network.
3. Open Minecraft, go to the **Servers** tab, and join one of these **redirect-compatible** Featured Servers: **Mineville, Lifeboat, Enchanted, Galaxite,** or **The Hive**. Instead of connecting normally, it'll open the BedrockConnect menu.
4. In BedrockConnect, choose **Add Server** and enter:
   - **Server Address:** `192.168.1.166`
   - **Port:** `19132`
5. Save and connect from the BedrockConnect list.

> Full setup guides and troubleshooting (including PS4/PS5 step-by-step DNS instructions) are on the [BedrockConnect GitHub page](https://github.com/Pugmatt/BedrockConnect).

> **Note:** `192.168.1.166` is a local network address, so this will only work while your console is on the same home network as the server. If you need to join from outside the house, ask the server admin whether port forwarding + a public address is set up.

---

## ❓ Troubleshooting

| Problem | Fix |
|---|---|
| Java client won't connect | Double-check you're on Fabric + Java 25, and your mod pack matches the server version |
| Bedrock client won't connect | Make sure you used port `19132`, not `25565` |
| "Outdated server/client" | The server and your mods may be on different Minecraft versions — re-download the mod pack |
| Can connect on LAN but not remotely | The server admin needs to confirm port forwarding is set up correctly |

---

## 📜 Server Rules

- [Add your rules here]

## 💬 Questions?

Reach out to [your contact / Discord link here].
