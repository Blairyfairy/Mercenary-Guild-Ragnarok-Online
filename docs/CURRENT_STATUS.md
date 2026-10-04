# Current Status – How the Mercenary Guild Works Now

## Core Systems (rAthena 2024–2026)

### 1. Three Guilds
- **Archer Mercenary Guild**
- **Spearman / Lancer Mercenary Guild**
- **Swordsman Mercenary Guild**

Each has its own faith value stored per character.

### 2. Faith (Loyalty)
- Increases when the mercenary kills monsters or stays alive.
- Higher faith unlocks better mercenaries and bonuses.
- Stored in `mercenary_owner` table (`arch_faith`, `spear_faith`, `sword_faith`).

### 3. Contract
- Limited duration (usually 30 minutes base, can be extended).
- Tracked by a timer on the mercenary.

### 4. Skills
- Full skill lists exist for levels 1–10 of each type.
- Both pre-renewal and renewal modes are supported.
- Status changes and cooldowns work.

### 5. Official NPCs
Located in `npc/other/mercenary_rent.txt`:
- Rent NPCs for each guild
- Faith checker / manager
- Related item shops

### 6. Commands
- `/merai` – switch between official and custom mercenary AI (exactly like `/hoai` for Homunculus).

## Database Tables
- `mercenary` – active mercenary instance
- `mercenary_owner` – faith and call counts per character

## What Still Can Be Improved on Private Servers
- More generous faith gain for mid-rate
- Extra convenience NPCs (this pack provides them)
- Better visual feedback for kill bonuses
- Custom high-tier mercenaries

This repository focuses on the last three points while documenting the solid foundation that already exists.
