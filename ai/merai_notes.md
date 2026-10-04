# Custom Mercenary AI (`/merai`) Notes

## Basic Usage
```
/merai
```
Toggles between official AI and the custom AI located in your client’s `AI/USER_AI/` folder (or the mercenary-specific file).

## Recommended Practice
1. Install a modern AI pack that explicitly supports mercenaries (many AzzyAI forks do).
2. Summon the mercenary.
3. Type `/merai` until the message confirms custom AI is active.
4. Test skill usage and aggression.

## Mid-rate Tips
- Make the mercenary more aggressive (lower HP threshold to start attacking).
- Enable automatic skill use.
- Watch SP – some high-level mercenaries can drain SP quickly on crowded maps.

## Files to watch
- `AI_M.lua` (classic location for mercenary AI)
- Any `USER_AI` files that contain mercenary logic

If the AI does nothing, the most common causes are the same as Homunculus:
- Wrong folder placement
- `/merai` still on Basic
- Outdated AI files
