# History – When the Mercenary Guild Did Not Work

## Original eAthena Era (≈ 2007–2012)

The Mercenary system was added relatively late and remained incomplete for a long time.

**Typical problems players and GMs faced:**

- Mercenaries could be summoned but many skills simply did nothing.
- Faith (loyalty) values often reset or never increased.
- Contract time was incorrect or expired instantly.
- Custom AI (`/merai`) frequently failed to load or caused Lua errors.
- Kill counter for stat bonuses was missing or broken.
- Pre-renewal and early renewal had different missing pieces.

Because eAthena development slowed dramatically, these bugs stayed for years on many private servers.

## Early rAthena (2011–2015)

rAthena inherited the code and began fixing it, but progress was gradual:

- Skill databases were incomplete.
- Status changes for mercenary skills were missing in pre-re.
- Visual effects and bonus announcements were absent.
- Some servers disabled the entire system because it was still unstable.

## Later Fixes (2016–2024)

Major improvements arrived over time:

- Full mercenary skill lists for both pre-re and renewal.
- Proper faith saving in `mercenary_owner` table.
- Working contract timers.
- `/merai` support became reliable with modern AzzyAI-style packs.
- 2023–2024 still saw small fixes (e.g. missing status icons on kill bonuses).

## Summary

| Problem                        | Old eAthena / early rAthena | Current rAthena |
|--------------------------------|-----------------------------|-----------------|
| Skills not working             | Very common                 | Fixed           |
| Faith not saving               | Common                      | Fixed           |
| Contract timer wrong           | Common                      | Fixed           |
| `/merai` unstable              | Common                      | Stable          |
| Kill bonus feedback missing    | Almost always               | Mostly fixed    |
| Pre-re / Renewal differences   | Broken                      | Supported       |

The system that “never worked” on old private servers now works correctly on any reasonably up-to-date rAthena.
