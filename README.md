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
  Flags likely smurfs and nicked players. *(Player stat lookups are switched
  off in this version while SmartQueue's Hypixel API application is reviewed;
  they show "no API key" until then.)*
- **Teammates**: for Bedwars Lobby 1. Set the stats you want in a teammate;
  anyone who mentions your name, messages you or invites you to a party is
  checked and marked Yes / Close / No. One click copies their name.
- **Player tags and notes**: tag players (e.g. Good teammate, Toxic) and see
  how many games you've played with each of them.
- **My Stats and Goals**: your own progress (FKDR, WLR, finals, wins, stars)
  today, this week and this month with simple graphs, your best and worst maps,
  plus daily, weekly, monthly and lifetime goals. Counted from your own
  Minecraft logs, including games played while SmartQueue was closed.
- **Radar**: the sweatiest and least sweaty maps of the last 7 days, based on
  how many strong players SmartQueue users met per game on each map.
- **Community cheater list**: players flagged by 5 different SmartQueue users
  are marked. Each account can flag 3 players a day; please flag only obvious
  cheating.

## How it works (and what it doesn't do)
- SmartQueue is a **separate program, not a Minecraft mod**. It reads the chat
  log your own Minecraft client already writes (`latest.log`) to see who is in
  your lobby. Vanilla, Forge, Lunar, Badlion, Feather and LabyMod are supported.
- It **never modifies the game, never sends chat or commands, never automates
  anything**, and doesn't read game memory or show anything the game hides.
- Player stats come from the official
  [Hypixel Public API](https://developer.hypixel.net/). SmartQueue's API key is
  kept on SmartQueue's server, never in the app, and you never need your own
  key. Results are cached so the same player isn't looked up again and again.
- Your own day/week/month stats come from your Minecraft logs, not from
  repeated Hypixel lookups. Your lifetime stats are looked up only when you
  open My Stats or Goals.
- The Radar shares only map, mode and counts for each game, never player names.
- It doesn't try to reveal who a nicked player really is.

## Account
SmartQueue uses a free account: sign in with Discord in your browser
(SmartQueue never sees your password), then link your Minecraft account. A
Minecraft account links when its Hypixel profile (My Profile -> Social Media
-> Discord) shows your Discord. Each account can link a main and 2 alt
Minecraft accounts and be signed in on 2 PCs.

## Support
Found a bug or have a question? Open an [issue](../../issues).

---
SmartQueue is an independent project. "Hypixel" and "Bedwars" belong to
Hypixel Inc.; "Minecraft" belongs to Mojang AB. This project is not affiliated
with either.
