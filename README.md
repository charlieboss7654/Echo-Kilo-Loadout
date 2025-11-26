# EKS Loadouts

A polished, modern, and fully configurable loadout & armoury system for FiveM, featuring realistic weapon distribution, Discord role permissions, MP Ped armourers, and a clean category-based UI.

This system is built for high-quality roleplay servers that want complete control over weapons, attachments, permissions, and armoury locations.


## Main Features

### Category-Based Loadout Menu
Organise loadouts into divisions, departments, or unit trees  
(e.g., **Police -> Firearms -> ARV Loadouts**).

### Customisable Loadouts
Each loadout supports:
- Weapons  
- Ammo  
- Attachments  
- Armour  
- Descriptions  
- Loadout-specific permissions  

All loadouts are defined in `config.lua` - no database required.

###  Discord Role Permissions (Badger_Discord_API)
Loadouts can require one or more Discord roles.

- If the player **has** the role -> loadout is usable  
- If the player **does NOT** have the role -> Loadout still appears, but **is greyed out and cannot be selected**


### Armoury System (Optional)
Enable armouries with:

- Multiple locations  
- Separate loadouts per armoury  
- ox_target or key-press interaction  
- Optional map blips  
- Per-armoury webhook logging  
- Base ped or **fully custom MP Ped** armourers

### Custom MP Ped Armourers
When using an MP Ped armourer, you can configure:

- Full head blend  
- Eye colour  
- Facial features  
- All overlays (beard, eyebrows, ageing, sun damage, etc.)  
- Hair style & colours  
- ALL clothing components  
- Props (hats, glasses, etc.)

Perfect for immersive, character-specific armoury clerks.

### Attachments Menu
Players can open a dedicated attachments window:

- Toggle weapon components  
- Apply changes instantly  
- Components update visually and reliably

### Safe & Optimised
- Client handles attachment logic  
- Server validates and gives weapons  
- Clean, readable structure  
- No performance-heavy loops

### Webhook Logging
Armoury withdrawals can be logged to Discord with:
- Player server ID  
- Loadout selected  
- Armoury location  
- Timestamp

## Installation

1. Drag the folder into your `resources/` directory.
2. Add to your `server.cfg`:

ensure EKS_Loadout

3. Configure everything in `config.lua`:

   * Loadouts
   * Categories
   * Attachments
   * Armoury locations
   * Discord role permissions
   * MP Ped appearance
   * Webhook URL


##  Dependencies

**Required**

* Badger_Discord_API - https://github.com/JaredScar/Badger_Discord_API

**Optional**

* ox_target (for armoury interaction)


## Support

Support is **not** provided in resource comments.
For help, bug reports, or custom development:

https://discord.gg/busQ9w6dqa

© Echo Kilo Studios
