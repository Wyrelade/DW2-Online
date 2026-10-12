<p align="center">
  <a href="https://discord.gg/nHXAq2fdCJ"><img src="https://img.shields.io/badge/Join%20Discord!-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Join Discord!"></a>
  <br>
  <sub>Community for DW2 Online and the PC port.</sub>
</p>

<p align="center">
  <img src="misc/banner.png" alt="Digimon World 2 Online" width="100%">
</p>

<h1 align="center">Digimon World 2 Online</h1>

<p align="center">
  An online version of <i>Digimon World 2</i> (PlayStation, 2000), built on the game's own code.
</p>

<p align="center">
  <a href="https://github.com/Wyrelade/DW2-Online/releases"><img src="https://img.shields.io/badge/Download-coming%20soon-555555?style=for-the-badge&logo=windows&logoColor=white" alt="Download: coming soon"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-pre--alpha-e05d44" alt="status: pre-alpha">
  <img src="https://img.shields.io/badge/version-v1.0%20pre--alpha-0078D6" alt="version: v1.0 pre-alpha">
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20Linux-lightgrey" alt="platform: Windows, Linux">
  <img src="https://img.shields.io/badge/price-free-2ea043" alt="price: free">
</p>

<p align="center">
  <img src="misc/screenshots/hub.jpg" alt="Tamers in the Main Gate of Digital City" width="97%">
</p>

<p align="center">
  <img src="misc/screenshots/new-account.jpg" alt="Log in and new account" width="32%">
  <img src="misc/screenshots/tamer.jpg" alt="Create your tamer" width="32%">
  <img src="misc/screenshots/hub-2.jpg" alt="Other tamers in the city" width="32%">
  <br>
  <img src="misc/screenshots/new-gaia.jpg" alt="Main Gate" width="32%">
  <img src="misc/screenshots/dna.jpg" alt="DNA digivolution" width="32%">
  <img src="misc/screenshots/digi-beetle.jpg" alt="Tamer status and Digi-Beetle" width="32%">
  <br>
  <img src="misc/screenshots/battle.jpg" alt="Battle" width="32%">
  <img src="misc/screenshots/terra-force.jpg" alt="Terra Force" width="32%">
  <img src="misc/screenshots/battle-2.jpg" alt="Battle" width="32%">
</p>

<p align="center"><sub>
  Pre-alpha screenshots, 16:9 at 1920x1080. The tamers in the city are test accounts.
</sub></p>

<p align="center">
  <a href="#about">About</a> &middot;
  <a href="#working-now">Working now</a> &middot;
  <a href="#planned">Planned</a> &middot;
  <a href="#devlog">Devlog</a> &middot;
  <a href="#faq">FAQ</a> &middot;
  <a href="#credits">Credits</a>
</p>

---

## About

DW2 Online is built on the [Digimon World 2 decompilation](https://github.com/Wyrelade/Digimon-World-2-Decomp)
and the [PC port](https://github.com/Wyrelade/DW2-PC). It adds accounts, a server and other
players.

This repository is the project page: screenshots, devlog and, later, downloads. The source code
is not published here.

> [!IMPORTANT]
> You will need your own copy of the game (USA, `SLUS-01193`). The downloads will contain no game
> data.

> [!NOTE]
> Pre-alpha. There is no public server yet, and everything here can change.

## Working now

- Log in or create an account from the title screen.
- Create a tamer: name, partner (Agumon, Patamon or DemiDevimon), Guard Team (Gold Hawk, Blue
  Falcon or Black Sword) and one of 35 looks.
- Your profile is stored on the server.
- Other tamers walk around Digital City with you, with name tags. Up to 49 are shown at once.
- The server checks movement in the city.
- After a short disconnect you can continue where you were.
- Smooth frames in the city, at your monitor's refresh rate.
- From the PC port: higher resolution, 16:9, gamepad, mouse in menus.

## Planned

These plans can change.

- Chat, friend list, player profiles.
- Domain runs started from domain items, with a level and extra rules.
- Item drops with random extra effects.
- Digimon quality: Normal, Fine, Rare or Shiny.
- Guard Teams with team chat and a team ladder.
- Market.
- Player versus player (PvP) battles.
- Tamer level. Higher levels unlock cosmetics such as profile pictures. Every domain is open at
  every level.
- The server decides battles, drops and rolls.
- Free, no shop.
- A first closed test.

## Devlog

Articles, newest first. All in [devlog/](devlog/).

- **2026-10-12** [Smooth frames](devlog/2026-10-12-smooth-frames.md)
- **2026-10-11** [Other tamers in the city](devlog/2026-10-11-the-city-is-shared.md)
- **2026-10-11** [Accounts and tamers](devlog/2026-10-11-accounts-and-tamers.md)
- **2026-10-10** [The plan](devlog/2026-10-10-the-plan.md)

## FAQ

**Is it free?** Yes.

**When can I play?** No date yet. News goes to [Discord](https://discord.gg/nHXAq2fdCJ) first.

**Do I need the original game?** Yes.

**Is the source code open?** No. The decompilation and the single player
[PC port](https://github.com/Wyrelade/DW2-PC) are open source.

## Credits

- **[Wyrelade](https://github.com/Wyrelade)**: project lead; the decompilation, the PC port and
  DW2 Online.
- DW2 file-format documentation by RmBeastbow.
- Thanks to ThirstyWraith for the stage overlay and battle notes.
- Built with [SDL3](https://libsdl.org/), [Dear ImGui](https://github.com/ocornut/imgui),
  [Mbed TLS](https://github.com/Mbed-TLS/mbedtls), [libsodium](https://libsodium.org/) and
  [PostgreSQL](https://www.postgresql.org/).

## Legal

Fan project, not affiliated with Bandai Namco or Toei Animation. Digimon World 2 and its
characters belong to their owners. No game data is in this repository. The banner is fan art.

---

<p align="center">
  <a href="https://nyen.cc/"><img src="https://nyen.cc/favicon.svg" alt="NYEN logo" width="32" height="32"></a>
  <br>
  <sub>Powered by <a href="https://nyen.cc/"><b>NYEN</b></a></sub>
</p>
