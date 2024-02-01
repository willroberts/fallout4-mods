# Fallout 4 Mods

This is a collection of mods for Fallout 4 on PC.
They were created with the Fallout 4 Creation Kit.

## fo4-survival-perks.esp

This mod tweaks the Perk system to streamline it for Survival mode.
It removes useless perks, condenses 5-point perks to save points, buffs defensive perks, and reorders some perks to improve build flexibility.
Combat-focused VATS perks have largely been reworked, especially those which previously granted damage or critical bonuses.

Changes:
- Perks which grant a chance for something to happen now explicitly state the chance.
- Removed Perks
  - Removes Strong Back 4 (fast travel while overencumbered), since fast travel is not available in Survival mode.
  - Removes Moving Target 3 (reduced Action Points drain while sprinting). Its bonuses have been moved to Blitz.
  - Removes Ricochet 3 (critical meter refill).
- Condensed Perks
  - 5-point damage perks (+20/40/60/80/100%) are now 4 points (+25/50/75/100%).
  - 5-point resistance perks (+10/20/30/40/50) are now 4 points, and have been buffed (+25/50/75/100).
- Modified Perks
  - Awareness 2 no longer grants increased damage in VATS.
  - Blitz no longer grants teleporting in VATS. It now grants reduced Action Points drain while sprinting at all ranks.
  - Concentrated Fire 3 no longer grants increased damage in VATS.
  - Demolition Expert 4 no longer grants increased damage when shooting mines in VATS.
  - Gun Fu no longer grants increased damage in VATS. It now grants reload speed at all ranks.
  - Life Giver now grants 25 Health per rank (up from 20), and has 4 ranks. The 4th rank also grants 1% Health regen when out of combat.
  - Nuclear Physicist no longer reduces Fusion Core drain. It now scales Radiation Damage by +50/100/150/200%.
  - Quick Hands 2 no longer grants free reloads in VATS. It now grants Action Points at all ranks.
  - Sniper 3 no longer grants VATS headshot chance. It now grants 30% knockdown chance.
- Reordered Perks
  - Changed the order of Perception perks, prioritizing defenses at lower ranks:
    - Refractor moved from 7 to 3
    - Sniper moved from 8 to 7
    - Awareness moved from 3 to 8
  - Changed the order of Intelligence perks, prioritizing crafting at lower ranks:
    - Scrapper moved from 5 to 1
    - Gun Nut moved from 3 to 2
    - Medic moved from 2 to 3
    - Science moved from 6 to 5
    - VANS moved from 1 to 6
  - Changed the order of Agility perks, prioritizing mobility at lower ranks:
    - Quick Hands moved from 8 to 4
    - Blitz moved from 9 to 5
    - Action Boy moved from 5 to 6
    - Gun Fu moved from 10 to 7
    - Moving Target moved from 6 to 8
    - Mister Sandman moved from 4 to 9
    - Ninja moved from 7 to 10

To Do:
- Luck rework
Current order:
- 1: Fortune Finder (Caps) = 1
- 2: Scrounger (Ammo) = 2
- 3: Bloody Mess (Damage) = 3
- 4: Ricochet = 10
- 5: Idiot Savant (XP) = 5
- 6: Mysterious Stranger (VATS) = 4 <-- remove critical meter bonuses
- 7: Better Criticals (Damage) = 6 <-- nerf multipliers, remove rank 3
- 8: Grim Reaper's Sprint (AP) = 8 <-- reduce chances, remove crit refill from rank 3
- 9: Four Leaf Clover (Refill) = 9 <-- reduce chances, remove rank 4
- 10: Critical Banker (Crits) = 7 <-- remove ranks 3 and 4