# Lucid Tarkov
## Escape from Tarkov PvE Cheat Suite — ESP, Aimbot, God Mode, Fly Hack, Item Spawner & More

[![Website](https://img.shields.io/badge/Website-lucid--script.pro-c8922a?style=flat-square)](https://lucid-script.pro/)
[![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/QPtxvk6MxU)
[![Latest Release](https://img.shields.io/github/v/release/Shurtug/Lucid?style=flat-square&color=c8922a)](https://github.com/Shurtug/Lucid/releases/latest)
[![Price](https://img.shields.io/badge/Price-%E2%82%AC5%2Fmo-lightgrey?style=flat-square)](https://lucid-script.pro/)

Download the latest launcher from the [Releases](https://github.com/Shurtug/Lucid/releases/latest) page. Join the [Discord](https://discord.gg/QPtxvk6MxU) for updates, setup help, and support.

---

## What Is Lucid Tarkov?

Lucid Tarkov is a **full-featured cheat suite for Escape from Tarkov's offline PvE mode**. It gives you complete control over your single-player raids — see every player and item with ESP, eliminate threats with a silent aimbot, become invincible with god mode, fly through maps with noclip, spawn any item from the game database, complete quests instantly, and much more.

The cheat is injected at runtime with **nothing written to disk**. The launcher downloads an encrypted module from our auth server, decrypts it in RAM using a session key tied to your HWID, and manually maps it into EFT. When you close the game, nothing is left behind.

**Supported Tarkov version:** auto-detected. The launcher selects the matching DLL for your installed game build — just keep the launcher updated.

## How It Works

```
Launcher                          Auth Server
┌────────────────┐                ┌──────────────────────┐
│ Enter license   │  encrypted    │ Validates key + HWID  │
│ key + HWID     │◄─────────────►│ Returns encrypted DLL │
│                │                │ (AES-256-GCM, HKDF)  │
└───────┬────────┘                └──────────────────────┘
        │ decrypt in RAM
        ▼
┌────────────────┐
│ EFT.exe        │
│ IL2CPP runtime │◄── manual map module (no disk write)
│ PvE raid       │    hooks game structures in memory
└────────────────┘
```

## Features

### ESP & Player Tracking
| Feature | Description |
|---|---|
| **Player ESP** | Bounding boxes, skeletons, health bars, distance, name tags, faction labels (PMC, Scav, Boss, Raider) |
| **Chams** | Separate player/gear/weapon material overrides with visible & invisible colours, scope/arms toggles |
| **Radar** | Top-down radar window with NPC/PMC/quest marker colours, adjustable size and range |
| **Exfil ESP** | All extraction points with activation status and distance |
| **Minimap** | In-raid overlay — satellite or abstract style, adjustable size/zoom/opacity, rotates with player |

### Loot ESP & Item Filtering
| Feature | Description |
|---|---|
| **Loot ESP** | Every loose item and container with price-tier colouring (common/rare/superrare) |
| **Value filter** | Min-rouble threshold — only see items worth picking up |
| **Quest items** | Highlighted separately with distinct colours |
| **High-tier gear** | High-penetration ammo and high-class armour auto-highlighted |
| **Wishlist filter** | Show only items you're looking for |
| **Crosshair focus** | Hover over items for details, adjustable radius, distance-based scaling |

### Silent Aimbot
| Feature | Description |
|---|---|
| **Silent aim** | Bone-targeted aim correction ("Magic Bullet" mode) |
| **Configurable FOV** | Adjustable target size and colour indicator |
| **Target priority** | PMC > Boss > Raider > Scav |
| **On-screen indicator** | Shows current target with adjustable colours |

### God Mode & Combat
| Feature | Description |
|---|---|
| **God Mode** | Zero damage coefficient, continuous full health restore every tick |
| **Infinite Stamina** | Body and hands stamina always at 100% |
| **No Hunger/Thirst** | Energy and hydration stay full |
| **Always Survive** | Survive any raid regardless of condition |
| **Thermal Vision** | Force thermal imaging with selectable palette and saturation |
| **No Visor** | Remove all helmet visor overlays |

### Movement
| Feature | Description |
|---|---|
| **Fly / Noclip** | WASD horizontal + Space/LCtrl vertical, clip through all geometry |
| **Speed Hack** | 1-10x movement speed multiplier, applied per physics tick |

### Item Spawner
| Feature | Description |
|---|---|
| **Spawn any item** | Full game database, searchable dropdown — weapons, armour, keys, quest items, everything |
| **Found-in-Raid toggle** | Mark spawned items as FiR |
| **Custom stacks** | Set stack amount, target slot override |
| **No slot restrictions** | Bypass inventory size limits |
| **Restore uses** | Refill key uses, medkit HP, fuel charges |
| **Resize backpack** | Custom width and height |

### AI Spawner
| Feature | Description |
|---|---|
| **Spawn any AI** | Scavs, PMC BEAR/USEC, Raiders, Rogues, Cultists, Infected |
| **All bosses** | Reshala, Killa, Shturman, Glukhar, Sanitar, Tagilla, Knight, Zryachiy, Kaban, Kolontay, Partisan, Wedge |
| **Adjustable difficulty** | Easy to impossible, configurable spawn count |
| **Spawn at position** | Spawns near you and teleports to your exact location |

### Quest Manager
| Feature | Description |
|---|---|
| **List quests** | Live status — available, started, completed, failed |
| **Complete quests** | Accept, complete, fail, or reset any quest |
| **Per-condition** | Complete individual quest conditions by ID |

### World Tools
| Feature | Description |
|---|---|
| **Unlock all doors** | One-click unlock for every door on the map |
| **Teleport AI** | Bring all bots to your position |
| **Instant search** | Open all container slots immediately, no animation |
| **Item teleport** | Pull all ground loot to your feet, filtered by rarity |

### Weapon
| Feature | Description |
|---|---|
| **No malfunction** | Disables jams, misfires, and overheating |
| **Infinite ammo** | Never run out of rounds |
| **Instant mag load/unload** | Zero-time magazine swaps |

### Player Stats
| Feature | Description |
|---|---|
| **Add EXP** | Instant experience points |
| **Trader reputation** | Set Fence, Prapor, Therapist, etc. to any level |
| **Skill levels** | Adjust any skill to any level |
| **Spoof nickname** | Display any name in-raid |

### Miscellaneous
- **Web dashboard** — control all settings remotely from your phone or any browser
- **Custom watermark** — configurable text, colour, and font size
- **OTA updates** — always the latest build, no manual downloads
- **Debug mode** — troubleshooting tools for support

## Supported Maps

Customs, Interchange, Reserve, Shoreline, Woods, Lighthouse, Streets of Tarkov, Factory, Labs, Ground Zero — every map in Escape from Tarkov.

## Requirements

| Requirement | Details |
|---|---|
| **Escape from Tarkov** | Any current version (auto-detected) |
| **Windows** | Windows 10 or 11 |
| **License key** | €5/month — [join Discord to purchase](https://discord.gg/QPtxvk6MxU) |

No second PC needed. No special hardware. Just the launcher and a license key.

## Update Policy

- IL2CPP memory layout maintained in-house — updated for every Tarkov build
- **OTA updates** — relaunch the launcher, it downloads the latest DLL automatically
- Typical update time: **hours** after a BSG patch
- HWID-locked licensing with automatic transfer after 56-day cooldown

## Getting Started

1. Join our [Discord server](https://discord.gg/QPtxvk6MxU) and purchase a license key
2. Download the latest launcher from [Releases](https://github.com/Shurtug/Lucid/releases/latest)
3. Run the launcher and enter your license key
4. Launch Tarkov, start an offline PvE raid, open the overlay menu
5. Full setup takes under 2 minutes

A detailed setup guide with screenshots is pinned in Discord.

## Also Available: Lucid Tarkov DMA

For hardware-level cheating via a PCIe DMA card on a second PC — hardware aimbot, ESP, loot radar, and memory-write cheats with zero footprint on your game machine. See [**Lucid Tarkov DMA**](https://github.com/Shurtug/LucidTarkovDMA).

## Support

Report bugs via the in-app Bug Description field, or reach out through [Discord](https://discord.gg/QPtxvk6MxU).

## Disclaimer

This software is designed for offline PvE use only. Use at your own risk. We are not responsible for any consequences of using this software.
