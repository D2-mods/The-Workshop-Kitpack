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
many new kit abilities
other misc items

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Components:
1. The Workshop Kitpack
2. Misc item pack
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
- Install after Rogue Rebalancing. Several RR files need to be patched for full compatiblity.
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
