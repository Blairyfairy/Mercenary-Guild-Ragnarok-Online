# Installation

## 1. Base Requirement
Make sure your rAthena already has the mercenary system enabled (it is by default).

Official file that should already exist:
```
npc/other/mercenary_rent.txt
```

## 2. Add This Pack’s NPCs

Copy:
```
npc/mercenary_guild_enhanced.txt
npc/mercenary_helpers.txt
```
into your `npc/custom/` folder.

Add to `scripts_custom.conf` (or equivalent):
```
npc: npc/custom/mercenary_guild_enhanced.txt
npc: npc/custom/mercenary_helpers.txt
```

## 3. Reload
```
@reloadscript
```

## 4. Optional – Custom AI
See `docs/MERAI_AI.md` and the `ai/` folder.

## 5. Verify
1. Talk to the enhanced Mercenary Guild NPCs.
2. Check faith values.
3. Summon a mercenary and confirm skills work.
4. Type `/merai` if you installed a custom AI.
