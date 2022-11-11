The Workshop Kitpack
GitHub: https://github.com/D2-mods/The-Workshop-Kitpack
Download: https://github.com/D2-mods/The-Workshop-Kitpack/releases


Info:
- Takes heavy inspiration from FromSoft's Soulsborne games, though only some names, short phrases, and ability concepts are taken directly from those games.

- The abilities tables for these kits are made at install time. Every kit clones the table of the base class (if it exists). This means that any class revisions installed before this mod will be included with these kits.

- If any spells were changed, then the revised spells may be learned by some kits. For example, the Confessor kit normally gains Blindness as a level 1 Priest spell. If you install Spell Revisions beforehand, it will instead gain Obscuring Mist.

- Compatible with BGEE, BG2EE, IWDEE, and EET. My original plan was to also be compatible with classic BG2, but it's probably too late for that. This mod makes heavy use of EE-only opcodes.

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

//misc
1 Holy Symbol     - for the cleric kit
4 Hunter Badges   - can be crafted (see below), can also be purchased
8 new spells      - learned by the Starjammer kit
other misc items (all general use items, no weapons or armor)

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
- These aren't hard rules, but compatibility will be best following these.
- Install after Rogue Rebalancing. Several RR files need to be patched for full compatibility.
- Install after class revision mods, unless they specifically say to install after any kits.
- Install after mods that revise or overwrite spells.

Spellcasting systems:
- Compatible with Faiths and Powers spheres system. Can install before or after FnP.
- Compatible with Deities of Faerun spheres system. Install this mod after DoF.
- Compatible with subtledoctor's 5e casting mod. Install this mod before 5e casting.
	- You should also install the extra component related to 5e casting.

HLA traps/songs:
- The Crow Hunter and Powder Keg kits need specific handling of HLA traps and songs. 
- Currently, this mod accounts for Rogue Rebalancing hlas.
- If you know of any others, let me know and I can add it.
- Only abilities gained by the base class are relevant for this.

There are no game-breaking errors if a file isn't patched. 
The unpatched HLAs just won't work 100% right with these kits.

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Version info:
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

- add_spell_ex by K4thos ((https://github.com/K4thos/IE-code-repository))

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
