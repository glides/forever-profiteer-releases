<p align="center">
  <img src=".github/icon.png" width="80" alt="Forever Profiteer">
</p>

<h1 align="center">Forever Profiteer</h1>

<p align="center">
  Gold-making for <b>World of Warcraft: Forever</b>: an addon plus a small desktop app that brings it<br>
  hourly prices for every Forever auction house in the US, EU, Korea and Taiwan, Blackwater included.
</p>

<p align="center">
  <a href="https://github.com/glides/forever-profiteer-releases/releases/latest/download/ForeverProfiteer-win-Setup.exe"><b>Download for Windows</b></a>
  &nbsp;·&nbsp;
  <a href="https://foreverprofiteer.com">Website</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/glides/forever-profiteer-releases/releases">All releases</a>
</p>

---

This repository only hosts the **installers and automatic updates**. To install, download the
setup file above (or pick a version under [Releases](https://github.com/glides/forever-profiteer-releases/releases)).

## Install

1. Download **`ForeverProfiteer-win-Setup.exe`** and run it. It installs for your Windows user only, so no admin rights are needed.
2. The app finds your WoW Forever folder, installs the **Forever Profiteer** addon and registers itself. There are no accounts or keys to set up.
3. Log in to WoW Forever, or type `/reload` if you're already playing. Prices refresh every hour while the app runs in your tray.

> **"Windows protected your PC"?** The installer isn't code-signed yet, so SmartScreen may warn you.
> Click **More info**, then **Run anyway**.

Prefer no installer? Each release also has a **portable** zip.

## What you get

| Addon | Desktop app |
| --- | --- |
| Tooltips with market value, sales per day, disenchant value and cost to make | Hourly prices for every Forever auction house in the US, EU, Korea and Taiwan |
| Search that opens auctions in place, favourites, range buying and one-click shopping lists | Two weeks of history, sales per day, sell rates, price trends, and prices per "of the X" gear version |
| Flips (faction and Blackwater), AH Disenchants, AH Vendors, Craft & DE, Craft & Sell | Your faction's AH, the other faction's and Blackwater, for your region |
| Farm tab with spawns on the world map, and a Mobs window ranked by gold per kill | Community drop rates for mobs, herbs, ore, skins and fishing |
| Bag post scan: post, vendor or disenchant, with AH deposits counted | Installs the addon and keeps it up to date |
| My Auctions: undercut checks, cancel queue, what's waiting in the mail | Updates itself quietly in the background |
| Gold dashboard and ledger across every character | Runs in the tray, starts with Windows if you like |
| Class and profession pages: disenchanting, cooldowns, tips, gathering, pickpocketing | |
| Answers `!pc [item]` price checks from friends and guildmates | |

The addon also works by itself without the app, using your own AH scans.

## Updating

The app checks for updates every few hours and installs them in the background. The tray icon tells you
when a restart will finish an update. The addon is updated along with the app, unless you turn that off in Settings or
manage the addon with another tool such as CurseForge.

## Uninstalling

Windows **Settings → Apps → Installed apps → Forever Profiteer → Uninstall**. Your addon settings and history live
in your WoW folder and aren't touched. To remove the addon too, delete
`Interface\AddOns\ForeverProfiteer` and `Interface\AddOns\ForeverProfiteer_Data` from your WoW Forever folder.

## Privacy

The app sends a random install ID, its version and the platform. It also shares **anonymous loot and gathering data** (which
mobs, herbs, veins and fishing spots you looted, what they gave, the coin on them) to build community drop rates. That's on by default and one click to turn
off in Settings; you get everyone's rates either way. Nothing from your game account, characters, realm or gold is
sent. See [foreverprofiteer.com/privacy.html](https://foreverprofiteer.com/privacy.html).

## Problems?

Open an [issue](https://github.com/glides/forever-profiteer-releases/issues). Please include the app version and the
lines from the app's **Activity** box.

---

<sub>Auction data from the Blizzard Entertainment Game Data API. World of Warcraft is a trademark of Blizzard
Entertainment, Inc. Forever Profiteer is a fan project and is not affiliated with or endorsed by Blizzard.</sub>
