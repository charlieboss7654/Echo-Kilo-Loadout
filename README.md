# EKS Loadouts

A clean, powerful, and fully configurable loadout system for FiveM! designed for realism, flexibility, and ease of use.

## Features

**Category-Based Menu**
Create structured loadouts by department or division (for example: Police ? Firearms ? ARV Loadouts).

**Fully Customizable Loadouts**
Each loadout can include:

* Weapons
* Ammo counts
* Components (attachments)
* Armour levels
* Custom weapon labels and descriptions

**Dynamic Attachments System**
Add, remove, or modify weapon attachments using an in-game UI.
Players can tick or untick attachments (flashlights, suppressors, scopes, etc.) and apply them instantly.

**Client-Side Precision**
Attachments are handled client-side for reliability, ensuring perfect syncing and instant visual updates.

**Server-Safe Logic**
The server still validates and dispatches loadouts, maintaining secure ownership handling.

**Lightweight and Optimized**
No database dependencies or unnecessary code. The entire system is config-driven and performance-safe.

## Installation

1. Drag and drop the folder into your `resources/` directory.
2. Add the following line to your `server.cfg`:

   ensure EKS_Loadouts
   
3. Edit `config.lua` to define your categories, loadouts, and attachment catalogs.

## Support

For support or to report issues, join our Discord and open a support ticket:

https://discord.gg/busQ9w6dqa
