# Mercenary Database Notes

## Official Location (rAthena)
- Pre-renewal: `db/pre-re/mercenary_db.yml` (or .txt on older versions)
- Renewal: `db/re/mercenary_db.yml`
- Skills: `db/mercenary_skill_db.txt` or YAML equivalent

## Key Points
- Each mercenary has an ID range for its guild (Archer / Lancer / Swordsman).
- Skills are assigned per mercenary level.
- Faith is **not** stored in the mercenary_db – it is stored per character in the `mercenary_owner` SQL table.

## Common Customisations Private Servers Make
- Increase base HP/SP for mid-rate
- Raise skill levels
- Add extra custom mercenaries
- Adjust contract duration in source or via NPC

This pack does not replace the official database – it only adds convenience NPCs on top of a working system.
