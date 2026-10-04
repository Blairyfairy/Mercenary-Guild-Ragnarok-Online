# Mercenary Guild for rAthena – History, Fixes & Enhanced Pack

**Complete GitHub-ready repository** for private Ragnarok Online servers.

This pack documents:

- When and why the Mercenary Guild **used to not work** properly
- How it **works now** on modern rAthena (and Hercules)
- Full working scripts
- Additional quality-of-life and mid-rate friendly features
- Custom AI notes (`/merai`)
- Ready-to-use NPC enhancements

---

## Quick History – Why It Used to Break

| Era | Project | Mercenary Status | Common Problems |
|-----|---------|------------------|-----------------|
| 2007–2011 | Original eAthena | Partially implemented | Missing skills, broken faith, no proper contract timer, AI barely worked |
| 2011–2013 | Early rAthena | Improving | Skills incomplete, pre-re/re mismatches, loyalty bugs |
| 2014–2020 | rAthena maturing | Mostly working | Occasional skill status bugs, missing visual effects |
| 2023–2026 | Current rAthena | Fully working | Minor polish still happens (e.g. bonus indicators) |

**Main historical issues:**
- Mercenary skills often did nothing or crashed the AI
- Faith / loyalty values did not save correctly
- Contract timers were inaccurate
- `/merai` custom AI was unstable or ignored
- Pre-renewal vs Renewal skill differences were incomplete
- Kill-counter bonuses had no visual feedback

These problems are largely solved in current rAthena master.

---

## Current Status (2026)

On a modern **rAthena** server the Mercenary Guild is fully functional:

- Three guilds: Archer, Spearman (Lancer), Swordsman
- Faith system per guild
- Contract duration and kill tracking
- Skills work in both pre-re and renewal
- Official rent NPCs exist (`npc/other/mercenary_rent.txt`)
- `/merai` switches between official and custom AI (same as `/hoai` for Homunculus)

---

## What This Pack Adds

1. **Clear documentation** of past problems → current working state
2. **Enhanced Mercenary Guild NPCs** with extra mid-rate friendly options
3. **Faith & Loyalty helper** NPCs
4. **Extra mercenary consumables** and convenience features
5. **Custom AI configuration notes** for `/merai`
6. Ready-to-drop scripts with proper comments

---

## Folder Structure

```
mercenary-guild-rathena/
├── README.md
├── LICENSE
├── docs/
│   ├── HISTORY.md              ← detailed “when it didn’t work”
│   ├── CURRENT_STATUS.md       ← how it works now
│   ├── INSTALLATION.md
│   └── MERAI_AI.md             ← custom mercenary AI guide
├── npc/
│   ├── mercenary_guild_enhanced.txt   ← improved rent + faith NPCs
│   └── mercenary_helpers.txt          ← extra convenience NPCs
├── db/
│   └── notes_mercenary_db.md
├── ai/
│   └── merai_notes.md
└── scripts/
    └── (optional extra scripts)
```

---

## Requirements

- rAthena (recommended) or a modern Hercules fork
- Mercenary system already compiled in (default)
- Basic knowledge of adding custom NPCs

---

**Enjoy reliable mercenaries on your private server.**
EOF
