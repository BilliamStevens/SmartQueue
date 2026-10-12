# SmartQueue

A stats overlay for **Hypixel Bedwars** on Windows. SmartQueue shows who is in
your lobby, how strong each player is, and helps you find good teammates and
track your own progress.

> **Not affiliated with or endorsed by Hypixel.** Use at your own risk.

## Download
Get the latest version from the [Releases](../../releases) page:
- **SmartQueue-Setup-&lt;version&gt;.exe**: installer (no admin rights needed)
- **SmartQueue-&lt;version&gt;-portable.zip**: unzip and run `SmartQueue.exe`

Windows may say "Windows protected your PC" because the app isn't code-signed
yet: click **More info -> Run anyway**.

## What it does
- **Lobby**: detects the players in your game and shows their Bedwars stats
  (stars, FKDR, WLR, finals, wins) with a threat level, most dangerous first.
  Flags likely smurfs and nicked players.
- **Teammates**: for Bedwars Lobby 1. Set the stats you want in a teammate;
  anyone who mentions your name, messages you or invites you to a party is
  checked and marked Yes / Close / No. One click copies their name.
- **Player tags and notes**: tag players (e.g. Good teammate, Toxic) and see
  how many games you've played with each of them.
- **My Stats and Goals**: your own progress with simple graphs, plus daily,
  weekly, monthly and lifetime goals.

## How it works (and what it doesn't do)
- SmartQueue is a **separate program, not a Minecraft mod**. It reads the chat
  log your own Minecraft client already writes (`latest.log`) to see who is in
  your lobby. Vanilla, Forge, Lunar, Badlion, Feather and LabyMod are supported.
- It **never modifies the game, never sends chat or commands, never automates
  anything**, and doesn't read game memory or show anything the game hides.
- Player stats come from the official
  [Hypixel Public API](https://developer.hypixel.net/). Results are cached so
  the same player isn't looked up again and again.
- It doesn't try to reveal who a nicked player really is.

## Account (coming soon)
An upcoming version of SmartQueue will use a free account (sign in with
Discord in your browser; SmartQueue never sees your password) linked to your
Minecraft account. Each account will be able to link a main and 2 alt
Minecraft accounts. The current version works without an account.

## Support
Found a bug or have a question? Open an [issue](../../issues).

---
SmartQueue is an independent project. "Hypixel" and "Bedwars" belong to
Hypixel Inc.; "Minecraft" belongs to Mojang AB. This project is not affiliated
with either.
