<p align="center">
  <img src=".github/icon.png" width="80" alt="Forever Profiteer">
</p>

<h1 align="center">Forever Profiteer</h1>

<p align="center">
  Gold-making for <b>World of Warcraft: Forever</b>: an addon plus a small desktop app that brings it<br>
  hourly auction prices for every US Forever auction house, including Blackwater.
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
| Tooltips with market value, recent lows and sales per day | Hourly price snapshots for every US Forever auction house |
| Flip finder that checks real demand | 14-day averages and sales-per-day estimates |
| Bag post scan: post, vendor or disenchant, with AH deposits counted | Prices for your own AH and Blackwater |
| Blackwater-aware prices, cut and My Auctions checks | Installs the addon and keeps it up to date |
| Disenchant values and a disenchant window (enchanters) | Updates itself quietly in the background |
| Shopping lists, gold dashboard and ledger | Runs in the tray, starts with Windows if you like |

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

The app sends only a random install ID, its version and the platform. Nothing from your game account, characters or
gold is sent. See [foreverprofiteer.com/privacy.html](https://foreverprofiteer.com/privacy.html).

## Problems?

Open an [issue](https://github.com/glides/forever-profiteer-releases/issues). Please include the app version and the
lines from the app's **Activity** box.

---

<sub>Auction data from the Blizzard Entertainment Game Data API. World of Warcraft is a trademark of Blizzard
Entertainment, Inc. Forever Profiteer is a fan project and is not affiliated with or endorsed by Blizzard.</sub>
