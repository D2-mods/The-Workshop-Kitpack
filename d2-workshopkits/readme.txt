The Workshop Kitpack
GitHub: https://github.com/D2-mods/The-Workshop-Kitpack
Download: https://github.com/D2-mods/The-Workshop-Kitpack/releases
Languages: English, French (by 11jo)


Info:
- Takes heavy inspiration from FromSoft's Soulsborne games, though only some names, short phrases, and ability concepts are taken directly from those games.

- The abilities tables for these kits are made at install time. Every kit clones the table of the base class (if it exists). This means that any class revisions installed before this mod will be included with these kits.

- If any spells were changed, then the revised spells may be learned by some kits. For example, the Confessor kit normally gains Blindness as a level 1 Priest spell. If you install Spell Revisions beforehand, it will instead gain Obscuring Mist.

- Compatible with BG:EE, BG2:EE, IWD:EE, and EET. My original plan was to also be compatible with classic BG2, but it's probably too late for that. This mod makes heavy use of EE-only opcodes.

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Mod contents:

//warrior kits
Beast Hunter (fighter)
Warhound (fighter)
Grave Warden (ranger)
Moonlight Knight (ranger)
Confessor (paladin)
Temple Knight (paladin)

//non-warrior kits
War Magician (mage)
Starjammer (sorcerer)
Blood Minister (cleric)
Crow Hunter (thief)
Powder Keg (bard)

//v3.0+ kits
Drifter (ranger)
Medic (monk)
Noble Scion (paladin)

//multiclass kits
Beast Hunter (f/m)
Beast Hunter (f/m/c)
Warhound (f/m)
Moonlight Knight (c/r)
Crow Hunter (f/t)
Crow Hunter (f/m/t)

//misc stuff
6 Hunter Badges   - can be crafted (see below), can also be purchased
8 new spells      - learned by the Starjammer kit
12 Caryll Runes   - items with party-wide effects
10 other items    - all general use items, no weapons or armor

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Components:
1. The Workshop Kitpack
2. Misc item pack (Note: Hunter Badges are part of main component)
3. Fix for subtledoctor's 5e casting mod

config.ini: Set a kit to = 0 to prevent install
Kit info: See GitHub page, in-game descriptions, forum posts, etc.

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Crafting a Hunter Badge (amulets):
- Certain kits will gain an ability to craft a Hunter Badge, once they reach a certain level.
- These abilities are gained only if a Beast Hunter is also in the party.
- Hunter Badges are usable by anyone, but Beast Hunters gain additional effects.
- Badges can only be crafted once each per playthrough.
NOTE: Beast Hunters don't gain a crafting ability, but they can still purchase these badges.

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Compatibility:

General guidelines:
- Install after Rogue Rebalancing. Several RR files need to be patched for full compatibility.
- Install after class revision mods, unless they specifically say to install after any kits.
- Install after mods that revise or overwrite spells.
- Install after mods that add new weapons or armor.

Spellcasting systems:
- Compatible with Faiths and Powers spheres system.
	- Can install before or after FnP (but I'd recommend after).
	- See below for additional info.
- Compatible with Deities of Faerun spheres system. 
	- Install this mod after DoF.
- Compatible with subtledoctor's 5e casting mod. 
	- Can install before or after 5e casting.
	- You should also install the extra component related to 5e casting.

HLA traps/songs:
- The Crow Hunter and Powder Keg kits need specific handling of HLA traps and songs. 
- Currently, this mod accounts for Rogue Rebalancing hlas.
- If you know of any others, let me know and I can add it.
- Only abilities gained by the base class need to be patched.

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

FnP additional info:
- The multiclass kits do not require the FnP multiclass mod for compatibility with FnP.
- For best compatibility, install this mod AFTER applying the sphere system.
- It will still work if installed before FnP, but some spheres may be incorrect (will update if it gets fixed).

FnP multiclass: 
- Current versions of FnP multiclass hide the F/M/C class from the selection screen. 
- It may possibly be updated to not disable F/M/C, but for now, there are a few ways around this:
1. Install this mod after FnP multiclass. It will automatically re-enable the class.
2. Use cdtweaks/Tweaks Anthology. It has components that make all classes (including FMC) available to all races.
3. Edit clsrcreq.2DA. Just find FIGHTER_MAGE_CLERIC, and set whichever races you want to 1.

This is how I'd do the install:
1. FnP spheres, kits, usability
2. The Workshop Kitpack
3. FnP multiclass kits (if using)
4. cdtweaks - enable all classes/multiclasses for all races

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Version info:

v3.1
- Fixes:
	- Drifter: Some enemy entangling effects were getting through.
	- Noble Scion: Wasn't able to use some Paladin items (i.e. Carsomyr).
	- SoD: The crafting abilities for hunter badges couldn't be learned.
- Changes:
	- Drifter: Added more mod spells to immunities lists (MiH spellpack, Deities of Faerun, sod2bg2).
	- Noble Scion: Self-damage from Blood Bullet won't kill the character if falling to 0 HP.
	- Oedon Writhe: Spell restore capped at 6th level spells.
	- Anti-Clockwise Metamorphosis: Movement speed bonus increased from +2 to +4.
- Beamdog items (bonus effects):
	- Archer's Eyes: Warhound, Warhound FM, Noble Scion
	- Belt of the Skillful Blade: Drifter
	- Screaming Bagpipes: Powder Keg
	- Stalker Gauntlets: Crow Hunter, Crow Hunter FT, Crow Hunter FMT
- Updated Compatibility info (with FnP mod):
	- I now recommend to install this mod after applying a FnP sphere system. See Compatibility section.
	- Fixed compatibility with FnP beta/v0.85 (Still backwards compatible with v0.84.5).

v3.0
- Fixes:
	- Fixed potential issue with IWDEE (caused by the file #BONECIR.SPL, if it was in the override).
	- Fixed Starjammer's Jolt spell effects when installed with the Deities of Faerun mod.
- Added kits:
	- Drifter (ranger)
	- Medic (monk)
	- Noble Scion (paladin)
- Kit/ability Changes:
	- Beast Hunter: "Fire Weapon" is now "Hunter Tools". Adds acid damage and boosts movement speed.
	- Grave Warden: Can wear up to chain mail (was previously leather).
	- Blood Minister: Will now gain Blood Tranfusion every 2 levels (max 10 uses).
	- Crow Hunter: Visceral Attack healing reduced from 20 HP to 12 HP.
	- All bleeding effects increased to 2 damage per round (affects Confessor kit, Crow Hunter kit, Clawmark Rune item)
	- Any kits that gain custom spells will learn them all in the spellbook at level 1.
- Item stuff:
	- Old/Saw Hunter Badges can now be crafted (by 2 of the new kits).
	- IWDEE: Changed conditions for obtaining certain items.
- Visual/Audio changes:
	- Changed visual/audio for War Magician's "Twisted Barricade".
	- Riftgate: Added portrait icon for the turn that the spell can't be recast.
	- A couple other minor changes (sounds or BAM images).
- Updated Compatibility section:
	- FnP note: The multiclass Cleric kits are currently not compatible with the beta versions of FnP. Use v0.84.5 if you want to use the multiclass kits with FnP.

v2.8
- What's new:
	- Added 2 Hunter Badges: Saw Hunter Badge and Old Hunter Badge.
	- Added 3 Caryll Runes: Hunter, Moon, and Milkweed.
	- Added Ether Limiter amulet (has bonus effect for Warhound kit).
	- Grave Warden: Can challenge Presio (IWDEE).
- Fixes:
	- Revitalizer: Fixed visual/audio effects not showing if the target was higher level than the caster.
- Changes:
	- Revised Jolt spell: Still raises dead, but also breaks curses and cures several status effects.
	- Changed a couple item locations to account for new items.
	- Calamity Ring: Added to expansion areas (SoD, ToB, HoW) if not already obtained.
	- Crowfeather Cloak: Added non-detection.
	- Cruciform: Will also give 2 bonus 2nd-level priest spell slots.

v2.7
- Fixes:
	- Beast Hunter (multiclass): Wasn't able to equip the "Big Metal Unit" armor (usable by every class/kit).
	- Grave Warden: Fixed potential usability issue on non-English installs of BG2EE.
	- Improved the way mass patching of spells/items by certain kits is handled.
	- A few other minor adjustments to install files.
- Changes:
	- Cosmic Watcher badge: Saving throw against the level drain is now made at a -2 penalty.
	- SoD: Changed one of the item locations.
	- Added a bag of holding, containing items from this mod (d2#hbag.ITM). Not obtainable from normal gameplay.

v2.6
- Improved icons for Caryll runes. The differences should be easier to see.
- Adjusted timings of a couple visual effects.
- Cleaned up some of the abilities tables (no gameplay effect)
- Some installer improvements.
- Updated some of my old functions files.

v2.5
- Added French translation, provided by 11jo.

v2.4
- IWDEE: Radiant Sword Badge now gives charm immunity (as per Protection From Evil in IWD)
- Confessor: Rooting Shot sets movement to 0 for the entangle. Previously, this could be broken by applying another movement effect. This is fixed. The entangled status can still be dispelled or removed by Free Action.
- Starjammer: More tweaks to Starjammer creature scripts (golem, gibberlings, balor)
- Renamed a few files for better organization (ability/item files are unchanged)
- Minor text edits (nothing important, I just make small edits sometimes)

v2.3
- Updated Compatibility section with info on the FnP multiclass mod.
- Kits are now selectable by any race if the base class is selectable. I made this change because there are some mods that enable all classes for all races, but don't enable all kits as well.
- The multiclass Cleric kits will now gain holy symbols at around 4 million xp (BG2 only):
	- Beast Hunter (FMC) gains it at Cleric level 14.
	- Moonlight Knight (CR) gains it at Cleric level 17.
	- This is compatible with any other mods or sphere system changes.
- Deities of Faerun: 
	- Revised spheres for most kits.
	- Multiclass clerics weren't gaining holy symbols, even at Cleric level 25. This is fixed (using above levels).
- Faiths & Powers: 
	- Revised spheres for multiclass clerics. 
	- My multiclasses don't require the FnP multiclass mod for compatibility with FnP.
	- I'd recommend installing this mod AFTER FnP multiclass, if using it. More info in Compatibility section.
- 5e casting mod: This mod can now be installed before or after 5e casting.

v2.2
- BGEE:
	- Status immunities should now block the correct display strings (they were only blocking the right strings in BG2). I went through abilities in each game to find the strings needed for each immunity. I still block a few "incorrect" strings in case some are used by other mods (they have the correct text, just not used by the game).
- IWDEE:
	- Healing Blood will cure poison now, rather than just slowing the damage. It was already working properly in the BG games. This mistake was made because I clone Slow Poison into a subspell, but forgot that it doesn't fully cure poison in IWD.
	- Status immunities should now block the correct display strings.
- Riftgate balor:
	- No longer immune to critical hits.
	- Summons Aerial Servants instead of a Fallen Planetar.
	- Changed some of the scripted spells.
	- Increased cooldown time for some script actions.
	- Can now re-summon creatures indefinitely (on a timed delay).
- Ether Booster (casting speed penalty):
	- Made it so the kit abilities from this mod are not affected by casting speed penalties (non-spell abilities shouldn't be affected anyways). Exceptions are Denial, Moonlight Vortex, and Bolt of Glory.
	- The Misc items component will also patch base game kit/NPC abilities and non-caster HLAs. Spell-like abilities, such as Shadowstep or Paladin abilities, are not patched.
- Golem Ring (haste/slow immunity):
	- In previous versions, simply equipping the ring would remove any haste or slow effects. At the same time, the Iron Flesh ability didn't give immunity to haste/slow, so you could cast it, then switch the ring out for a different one.
	- I changed it so that equipping the ring won't remove any effects. It will just prevent future effects while equipped. Using Iron Flesh, however, will now remove any haste or slow effects, as well as make the character immune to both for the duration.
- Beast's Embrace: Added effect to account for an EE Fixpack change.
- Cruciform: Changed portrait icon to the standard "Regenerating" one used by other items/spells.
- Blood Transfusions: Added additional portrait icons ("Protection From Poison", etc.).
- Corruption rune: Will now show a "Regenerating" icon, but only when under 50% HP.
- Some other minor adjustments.

v2.1
- Config.ini: Added proficiencies option for multiclass Clerics. If enabled, can place slots in all weapon types. This does not change usability by itself. This option is for use with tweaks that enable all weapons for Clerics. Note that this is automatically enabled if this mod is installed after Deities of Faerun or the Faiths and Powers usability component.
- Rearranged order that kits are installed (Arcane kits moved to top).
- Moonlight Knight (C/R): It was able to place slots in all weapon types by default, even though Cleric/Rangers are normally restricted to Cleric weapons. This is fixed.
- Ether Booster: Bonus effect is applied immediately when Unleash Magic is used. The effect is applied every 3 seconds, but previously you had to wait 3 seconds for it to start.
- Cruciform: Bonus effect is applied immediately when Bloodletter is used.
- Hunter Badges: Bonus effects are applied immediately when Fire Weapon is used.

v2.0
New additions
- Added 6 multiclass variants:
	- Beast Hunter (f/m)
	- Beast Hunter (f/m/c)
	- Warhound (f/m)
	- Moonlight Knight (c/r)
	- Crow Hunter (f/t)
	- Crow Hunter (f/m/t)
- These are installed together with the single classes. As with the single class, each kit can be enabled or disabled from the config.ini file.
- Added 9 Caryll Runes to Misc items component. These are items with party-wide effects, inspired by the similarly named items from Bloodborne. See GitHub page or forum posts for more details.

Fixes/Tweaks:
- Blood Minister
	- DoF sphere system: Added weapon restrictions (blunt, crossbows, small piercing weapons). These are implemented the same way as Raduziel's own kits (added directly to weapon files). This kit also wasn't getting "All" spheres up to 7th level. This is fixed.
	- FnP sphere system: Will now gain higher level healing spells, in addition to previous spheres.
- Frenzying Flame: Added audio while the spell is active
- Craft Hunter Badge: Added info about using the ability when right-clicking the icon
- Fixed WeiDU error when installing after FnP.
- Fixed proficiencies for Paladin and Ranger kits when installed after FnP.
- Updated ADD_KIT_EX to v0.5.1


v1.5
- Starjammer: Minimum stats changed to be different from Dragon Disciple

v1.4
- Added spell cap option to config.ini: This affects 2 spells, Electrocannon and Revitalizer (Starjammer kit). The cap can be set to level 20, 30, 40, or 50. Any other number will revert to the defaults (20 for BG games and 30 for IWDEE).
- More edits to the Riftgate balor (both buffs and nerfs). If you're unprepared for it, best thing to do would be to run to a different map (it will search you out if on the same map). It's also vulnerable to Imprisonment, if you can get the spell off.
- Added 2 items to the "Misc items" component:
	- Stone Ring
	- Flynn's Ring
- Golem Ring ability now says "Iron Flesh" by the portrait icon to differentiate from Stoneskin.
- Might have made a few other minor adjustments.

v1.3
- Powder Keg: Fixed minor issue when installed after Rogue Rebalancing. The kit was starting with the RR song, though you could switch right away to Blasting Song. Now the kit starts with Blasting Song set as the Bard Song.

v1.2
- One item in SoD was gained without charges. This is fixed.
- Revised the balor script (Riftgate enemy). It has more spell variety, but also doesn't use annoying spells like Death Spell or Remove Magic as often. It no longer starts with Protection From Magical Weapons, but it has a couple summons instead. The phase 2 and phase 3 buffs also happen earlier.
- Also made minor edits to the golem and gibberling scripts.

v1.1
- Added Cosmic Watcher Badge to BG2 and IWD main campaigns (they were already in the expansions). Both are very late game.
- Adjusted location of one of the other badges in BG2.

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Custom functions (not including my own):
- ADD_KIT_EX by Argent77 (https://github.com/Argent77/A7-add_kit_ex)

- CD_EXTEND-O-MATIC by Camdawg (https://www.gibberlings3.net/forums/topic/28835-toss-your-semi-useful-weidu-macros-here/#comment-254220)

- add_spell_ex by K4thos (https://github.com/K4thos/IE-code-repository)

- immunity batch macros from BG2 Fixpack (https://www.gibberlings3.net/forums/topic/28834-bg2-modder-resource-effect-batch-macros)

- immunity spellstates from EE Fixpack (https://www.gibberlings3.net/forums/topic/35616-effect-immunities-on-the-ee-engine-aka-taking-full-advantage-of-the-ee-fixpack)

- RA_SPHERE_COMPAT.tpa for Deities of Faerun mod (https://github.com/Raduziel/Deities-Of-Faerun/releases)

- fnp_compatibility.tpa for Faiths & Powers mod (https://github.com/UnearthedArcana/Faiths_and_Powers/releases)

- semi_spontaneous.tpa for 5e casting mod (https://github.com/UnearthedArcana/5E_spellcasting/releases)

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Tools/Resources used to make this mod:
- WeiDU (https://github.com/WeiDUorg/weidu)
- NearInfinity (https://github.com/Argent77/NearInfinity)
- Notepad++ (https://notepad-plus-plus.org/)
- paint.net (https://www.getpaint.net/)
- IESDP (https://gibberlings3.github.io/iesdp/main.htm)
- WeiDU readme (https://weidu.org/~thebigg/README-WeiDU.html)
- Infinity Auto Packager (https://github.com/InfinityTools/InfinityAutoPackager)
- Git Bash (https://git-scm.com/downloads)

Original game resources included with this mod belong to the rights holders.
These files are packaged with the mod to account for possible missing files.
