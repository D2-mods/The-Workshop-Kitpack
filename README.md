# The Workshop Kitpack

Download: https://github.com/D2-mods/The-Workshop-Kitpack/releases  
Forum posts: [Beamdog](https://forums.beamdog.com/discussion/86749/mod-the-workshop-kitpack), [Gibberlings3](https://www.gibberlings3.net/forums/topic/36122-the-workshop-kitpack/)  
Languages: English, French (JohnBob)

--

This is a kitpack I've been working on for a while. It currently has 17 kits + 11 multiclass variants. Also adds 30+ items, including 6 Hunter Badges, 12 Caryll Runes, and 17 other misc items. Heavily inspired by FromSoft's Soulsborne games and probably other sources. Compatible with BG:EE, BG2:EE, IWD:EE, and EET.

NOTE: The abilities tables for these kits are made at install time. Every kit clones the table of the base class (if it exists). This means that any class revisions installed before this mod will be included with these kits.

--

Kit Updater: Run this after all tweak and overhaul mods (except possibly Dual to Kit). It rebuilds HLA lists and updates proficiencies + some other minor checks. It also includes the previous "Update Medic Arts" component (use if Poison Weapon or Lay On Hands were revised). More info in Components section.

--

![Preview image](d2-workshopkits/preview/preview2.webp)

--

Mod contents:
-

#### Warrior kits
- Beast Hunter (fighter)  
- Warhound (fighter)  
- Grave Warden (ranger)  
- Moonlight Knight (ranger)  
- Confessor (paladin)  
- Temple Knight (paladin)

#### Non-warrior kits
- War Magician (mage)  
- Starjammer (sorcerer)  
- Blood Minister (cleric)  
- Crow Hunter (thief)  
- Powder Keg (bard)

#### v3.0 kits
- Drifter (ranger)
- Medic (monk)
- Noble Scion (paladin)

#### v4.0 kits
- Full Metal Jaguar (fighter)
- Nurse (thief)
- Spell Fencer (fighter/mage)

#### Multiclass variants
- Beast Hunter (FM, FMC, FC)
- Warhound FM
- Moonlight Knight CR
- Crow Hunter (FT, FMT, MT)
- Full Metal Jaguar (FM, FT)
- Nurse MT

#### Misc stuff
- 6 Hunter Badges&emsp;- can be crafted (see below), can also be purchased  
- 8 new spells&emsp;&emsp;&emsp; - learned by the Starjammer kit  
- 12 Caryll Runes&emsp;&emsp;- items with party-wide effects
- 17 other items&emsp;&emsp;- all general use items, no weapons or armor

--

Components:
-
1. The Workshop Kitpack
	- Option 1: Base kits + multiclass variants
	- Option 2: Base kits only
	- Option 3: Misc items only (no kits or Hunter Badges)
2. Misc item pack
	- Option 1: Standard Install
	- Option 2: Dev mode (start with Item Sack)

--

**Extra patching:**
- Kit Updater (fixes or updates, see below)

#

**Additional Info:**
- If Option 1/2 is installed, then "Misc items" will be the next (separate) component.
- If Option 3 is installed, it will skip the rest of the components.
- Hunter Badges are installed together with the Beast Hunter kit.

**Kit Updater:**
- Updates HLA tables, Proficiencies, misc fixes, mod compat, etc.
- Skipped on initial mod install, can be re-run at any time (does not uninstall other mods).
- Run after all tweak and overhaul mods, including mods that say to install last.
- Dual to Kit note: Run this once before Dual to Kit if using a proficiency tweak. It can be re-run after if you need to update other things later. (note: it's specifically component 3 of Dual to Kit that needs to be after any proficiency edits)

**Config:**
- config.ini: Set a kit to = 0 to prevent install
- Disabling a single class will also skip the multiclass variants.
- There are several other options. These should be set before the mod is installed.
- Some options can now be changed with the Kit Updater (these are clearly marked).

--

Kit descriptions:
-

<details>
  <summary>Warrior kits:</summary>

---

**Beast Hunter (Fighter)**

BEAST HUNTER: Wherever there are beasts, there are hunters. Hunters may be protectors or mercenaries, or simply have an addiction for blood and slaughter. This class is particularly adept at combating several powerful types of monsters, including demons and werewolves.

Advantages:
- +3 bonus to attack and damage rolls vs. lycanthropes and fiendish creatures.
- 2nd level: May use the Hunter Tools ability once per day. Gains additional uses every 4 levels thereafter.

HUNTER TOOLS: For 12 rounds, the character gains a +1 bonus to luck rolls and Saving Throws, and melee attacks deal an extra 1d3 acid damage. This ability can be enhanced by equipping special Hunter Badges.

- 5th level: May use the Quicksilver ability once per day. Gains additional uses at levels 9 and 13.

QUICKSILVER: Enhances ranged attacks for 6 rounds, adding 2 points of piercing damage and a +5% chance to score a critical hit. All ammo types (arrows, bolts, and bullets) are also enchanted and become able to hit enemies that normally require magical or silver weapons to hit.

- 8th level: +2 bonus to AC and Saving Throws vs. lycanthropes and fiendish creatures.
- 16th level: Additional +5% to critical hit chance with Quicksilver.

Disadvantages:
- May not wear armor heavier than studded leather.
  
---

**Warhound (Fighter)**

WARHOUND: Warhounds are armored soldiers specializing in long-range warfare. They are often members of elite squadrons, overwhelming enemy armies with a barrage of missiles.

Advantages:  
- +1 bonus to Armor Class vs. missile, plus an additional +1 bonus every 5 levels.  
- +1 to ranged attack and damage rolls at 3rd level and an additional +1 bonus every 5 levels thereafter.
- May achieve Grand Mastery (5 slots) in longbows, shortbows, crossbows, slings, and darts.  
- May use the Shockwave and Incinerate abilities. Gains one use each at level 4, plus an additional use each every 4 levels, up to a maximum of 5 uses each at level 20.

SHOCKWAVE: The next successful ranged attack explodes in a 15-ft. radius, inflicting 3 + 2d4 crushing damage for every 4 levels of the character, up to a maximum of 3 + 10d4 at level 20. Any enemies in the blast are also propelled back a considerable distance (no save).

INCINERATE: The next successful ranged attack creates a fiery cloud, which covers a 15-ft. radius and lasts for 4 rounds. Once each round, creatures in the cloud suffer 1d6 fire damage per 4 levels of the character, up to a maximum of 5d6 at level 20 (Save vs. Breath for half).

Disadvantages:  
- May not Specialize in melee weapons.  
- May not Specialize in any fighting style.

---

**Grave Warden (Ranger)**

GRAVE WARDEN: Far to the east, the Grave Wardens tend to the tombs of the slumbering dead, ensuring they remain undisturbed. They are guardians, guides, deterrents, and storytellers, and possess a unique ability to deny death.

Advantages:  
- +4 bonus to Saving Throws vs. Death.
- +10 bonus to Lore each level.  
- May cast three arcane spells as priest spells:  
	1st level: Chromatic Orb.  
	2nd level: Horror.  
	3rd level: Skull Trap.

- 3rd level: Immune to fear and morale failure.
- 5th level: May use the Denial ability once per day. Gains additional uses every 5 levels thereafter.

DENIAL: This spell has two effects. First, the recipient becomes immune to all forms of death magic for 3 turns. Second, if the recipient falls below 50% of maximum Hit Points, the spell activates and restores the character to full health, consuming the spell in the process.

- 8th level: Immune to blindness and gaze attacks.

Disadvantages:  
- May not wear armor heavier than chain mail.
- May not use the Charm Animal ability.
- Alignment restricted to non-evil and non-chaotic.

---

**Moonlight Knight (Ranger)**

MOONLIGHT KNIGHT: A forlorn warrior, branded by the Moonscar, having dreamed a dream of endless moonlight. Partakes in pilgrimage to moonlit altars, seeking a revelation from things unseen.

Advantages:
- Moonscar: +1 bonus to all Saving Throws. The bonus becomes +2 at level 8 and +3 at level 16.
- 3rd level: Gains the Torrent ability (passive).

TORRENT: On a successful attack (melee or ranged), the character has a 10% chance to be hasted for 10 seconds, gaining an extra attack per round and doubled movement rate. At 8th level, attacks deal an extra 2 points of magic damage. At 16th level, Attacks Per Round is doubled. For the duration, the effects of Moonscar are also reversed.

- 7th level: May use the Moonlight Vortex ability once per day. Gains additional uses every 4 levels thereafter.

MOONLIGHT VORTEX: Unleashes a beam of torrential moonlight, which extends as far as the target point, inflicting 8d6 magic damage to enemies. Undead and outerplanar creatures take double damage from this spell. In addition, residual moonlight, left behind from the casting, grants the character a +20% bonus to Magic Resistance for 4 rounds.

- No alignment restrictions.
- Will not fall due to reputation loss.

Disadvantages:
- Moonscar: -1 penalty to AC vs. slashing, piercing, and missile. The penalty becomes -2 at level 8 and -3 at level 16.
- Only has half the normal skill in Hide In Shadows and Move Silently.

---

**Confessor (Paladin)**

CONFESSOR: The Confessor is a paladin who acts on behalf of a patron church, being adept at a variety of duties, including, but not limited to, gathering intel, exposing untruths, and hunting down enemies of the church.

Advantages:  
- May cast four arcane spells as priest spells:  
	1st level: Blindness.  
	2nd level: Blur.  
	3rd level: Vampiric Touch.  
	4th level: Secret Word.

- 2nd level: May use the Rooting Shot ability once per day. Gains additional uses every 4 levels thereafter.

ROOTING SHOT: The next successful ranged attack entangles the target for 3 rounds, plus an additional 3 rounds on a failed save vs. Spell. An entangled creature can still attack, but suffers a -2 penalty to Armor Class and a 20% chance of spell failure.

- 5th level: May use the Bloodletter ability once per day. Gains additional uses at levels 9 and 13.

BLOODLETTER: For 5 rounds, each successful melee attack restores 1d4+1 Hit Points. As well, the target suffers a bleeding wound, taking 2 points of damage per round for 6 rounds (no save). A target can be wounded once per round and the effects are cumulative.

Disadvantages:  
- May not wear armor heavier than studded leather.  
- May not use the Lay On Hands ability.

---

**Temple Knight (Paladin)**

TEMPLE KNIGHT: These heavily-clad knights can be found guarding the sanctity of temples and churches throughout Toril. They are righteous soldiers, who stand unwavering against any adversary.

Advantages:  
- May achieve High Mastery (four slots) in polearms and blunt weapons.  
- May use the Lay On Hands ability three times per day.  
- 2nd level: May use the Force ability once per day. Gains additional uses every 4 levels thereafter.

FORCE: Creates a shockwave. Inflicts no damage, but staggers nearby foes. All enemies within 15 feet are propelled back and stunned for 4 seconds (no save). Huge creatures are stunned only momentarily and will not be knocked back.

- 9th level: May cast Bolt of Glory as a special ability once per day. Gains additional uses at levels 13 and 17.

Disadvantages:
- May not Specialize in ranged weapons.
- Turns undead at 2 levels lower than other paladins (starting at 5th level).

---

</details>

<details>
  <summary>Non-warrior kits:</summary>

---

**War Magician (Mage)**

WAR MAGICIAN: The War Magician learns to draw out and amplify innate magical energies, gaining abilities beyond that of a normal wizard, though the process is very physically draining.

Advantages:  
- +10% bonus to fire, cold, electricity, acid, and magic damage resistances. Gains an additional +5% bonus every 5 levels, up to a maximum of 30% at level 20.  
- May use the Unleash Magic and Twisted Barricade abilities. Gains one use each at level 2 and an additional use each every 4 levels thereafter.

UNLEASH MAGIC: The caster reverses elemental energies. For 4 rounds, each resistance bonus becomes a -10% penalty and the character gains a +10% bonus to all elemental and magic damage dealt, as well as a +2 bonus to caster level. The bonuses and penalties increase as the caster's innate resistance bonuses increase.

TWISTED BARRICADE: For 4 rounds, each resistance bonus is tripled and all normal missiles are deflected away harmlessly. While in effect, the character's movement is slowed by half. Starting at 10th level, any spells cast against the character will also be deflected, excluding area attacks.

Disadvantages:  
- Incurs a -2 penalty to Strength and Constitution.

---

**Starjammer (Sorcerer)**

STARJAMMER: Starjammers are drifters from beyond the stars who escaped a great Evil on their home planet, with several finding their way to Toril. As outsiders, they resemble powerful sorcerers, though the destruction of their home, and the subsequent flight, has taken a toll mentally and physically.

Advantages:  
- Unaffected by magical spell failure, deafness, or silence.  
- Gains immediate access to a number of kit-specific spells, up to 8th level: Riftstep, Steady Current, Gemini Swap, Pacifying Field, Jolt, Electrocannon, Revitalizer, and Riftgate.  
- 5th level: May use the Interference ability once per day. Gains additional uses every 5 levels thereafter.

INTERFERENCE: Disrupts missile and spell attacks in the area of effect. All enemies in a 30-ft. radius suffer a -3 penalty to ranged attack rolls and a 25% chance of spell failure for 1 turn (no save). The penalties increase by -1 to attack rolls and +5% spell failure every 5 levels thereafter.

Disadvantages:  
- Incurs a -2 penalty to Dexterity and Wisdom.

---

**Blood Minister (Cleric)**

BLOOD MINISTER: The heretical Healing Church was once the home of blood ministration, a medical remedy said to have the ability to cure any disease, whether natural or god-stricken. More recently, priests of the Healing Church have begun appearing again along the Sword Coast.

Advantages:  
- Immune to level drain, poisons, and diseases.  
- May use the Blood Transfusion ability. Gains one use at level 2 and an additional use every 2 levels, up to a maximum of 10 uses at level 20. When this ability is used, it opens a submenu with a list of transfusions. New transfusions become available at higher levels:  
	- 2nd level: Healing Blood.  
	- 6th level: Beast Blood.  
	- 10th level: Madman's Blood.  
	- 14th level: Lead Elixir.

HEALING BLOOD: Blood drawn from a nun of the Healing Church. Restores 15% of maximum Hit Points and grants the miracle of regeneration, healing an additional 2 Hit Points per round for 3 turns. While in effect, the recipient incurs a -1 penalty to attack rolls. This blood will also cure any poisons or diseases.

BEAST BLOOD: Administer medicinal blood that grants temporary Beasthood for 3 turns. The recipient gains a +1 bonus to damage, and each successful melee attack gives an additional +1 bonus to damage for 2 rounds. While in effect, the recipient incurs a -3 penalty to Armor Class. This blood will also prevent any poisons or diseases.

MADMAN'S BLOOD: Administer medicinal blood that grants insight into the Cosmos. The recipient gains +4 to all mental Attributes, +5% Magic Resistance, and a +1 bonus to casting speed, but incurs a -1 penalty to all Saving Throws. The effects last for 3 turns. This blood will also cure level drain.

LEAD ELIXIR: A mysterious concoction that shifts weight to boost defense and resilience. The recipient gains a +4 bonus to Armor Class and Saving Throws, and 20% resistance to all damage types, but incurs a -1 penalty to luck rolls. The effects last for 3 turns. This blood will also prevent level drain.

Disadvantages:  
- May not wear magic gauntlets or bracers.

---

**Crow Hunter (Thief)**

CROW HUNTER: A Crow Hunter acts swiftly and mercilessly against the chosen mark. This is a Hunter of Hunters, an experienced killer, and feared, though not necessarily cruel or evil, despite the unsavoriness of the work.

Advantages:  
- +1 bonus to attack and damage rolls vs. humans, demihumans, and smaller humanoid races. The bonus increases to +2 at level 5 and +3 at level 10.
- 4th level: May use the Splintering Shot ability once per day. Gains additional uses every 4 levels thereafter.

SPLINTERING SHOT: For 3 rounds, each successful ranged attack bursts into multiple sharp splinters. All enemies in a 15-ft. radius take 2 points of piercing damage and suffer a bleeding wound, which inflicts 1 point of damage per round for 1 turn (no save). A target can be wounded once per round and the effects are cumulative.

- 9th level: May use the Visceral Attack ability once per day. Gains additional uses at levels 13 and 17.

VISCERAL ATTACK: The next melee attack within one round has a 100% chance to score a critical hit. This attack will also restore 5 + 20% of maximum Hit Points and haste the character for 10 seconds.

Disadvantages:  
- Only gains 20 thieving skill points per level.
- May not use the Set Snare ability.

---

**Powder Keg (Bard)**

POWDER KEG: The Powder Kegs are a faction of bards, known for their love of intricate mechanical weapons and big booms. Their instruments double as incendiary devices and may cause a variety of other explosive effects.

Advantages:  
- 10% resistance to fire, and increases by +10% every 5 levels, up to a maximum of 50% at level 20.
- Gains Bard Songs unique to the Powder Kegs. Songs can be switched between from the special abilities menu. New songs become available at higher levels:  
	- 1st level: Blasting Song.  
	- 5th level: Booming Song.  
	- 10th level: Dust Explosion.  
	- 15th level: Frenzying Flame.

BLASTING SONG: A ring of flame bursts outwards in a 15-ft. radius, dealing 1d4 fire damage per level to all except the bard, up to a maximum of 20d4 at level 20 (Save vs. Breath for half). Initial pyrotechnics inflict an extra 2 points of fire damage to enemies in a 12-ft. radius.

BOOMING SONG: A crushing wave expands outwards in a 15-ft. radius, dealing 3d8 crushing damage to enemies and causing deafness for 2 rounds, plus an additional 2 rounds on a failed save vs. Spell. Deafness causes a 50% chance to miscast spells.

DUST EXPLOSION: The initial blast inflicts 8d6 fire damage to enemies in a 15-ft. radius (Save vs. Breath for half). In addition, a cloud of dust and smog lingers for 3 rounds and shrouds a 20-ft. radius. All creatures in the cloud are blinded and become invisible, and enemies also have movement slowed by half.

FRENZYING FLAME: Spreads a frenzy-inducing flame that envelopes a 20-ft. radius and lingers for 2 rounds. Any enemy entering the flames immediately suffers the effects of sleep, confusion, fear, or berserk for 5 rounds (25% chance of each). Enemies also take 2d12 magic damage per round while in the area. There is no Saving Throw, though Magic Resistance can prevent the status effects.

- If the "Enhanced Bard Song" HLA is learned, the character will gain an ability to switch to this song.

Disadvantages:  
- Bard Song is disabled for 8 rounds after each use.
- Only has one quarter the normal Pick Pockets score.

---

</details>

<details>
  <summary>v3.0 kits:</summary>

---

**Drifter (Ranger)**

DRIFTER: An aimless wanderer, at home in adverse terrain. Countless battles have honed the abilities of these finely skilled warriors.

Advantages:
- +4 bonus to Saving Throws vs. Breath.
- +1 bonus to Armor Class, plus an additional +1 bonus every 5 levels.
- +1 to attack and damage rolls at 3rd level and an additional +1 bonus every 5 levels thereafter.
- Will not fall due to reputation loss.
- Moves 2 points faster than other characters.
- 6th level: Immune to Grease, Web, Entangle, Spike Growth, and Spike Stones.
- 7th level: Gains the Evasion ability (passive).**
- 12th level: Immune to Cloudkill, Death Fog, Stinking Cloud, Writhing Fog, and Cloud of Pestilence.

Disadvantages:
- May not cast priest spells.
- May only wear leather or hide armor.
- Alignment restricted to any non-lawful.

--

**\*\*Supported Evasion versions:**  
&emsp;Icewind Dale: Enhanced Edition  
&emsp;IWDification  
&emsp;Talents of Faerûn

---

**Medic (Monk)**

MEDIC: This Monk is a skilled medical practitioner, as well as warrior, and has undergone special training, applying powerful herbal remedies to aid in combat.

Advantages:
- Gains Ki Energy, which is used to activate kit abilities. Gains +1 to maximum Ki Energy every 2 levels (starting at 1st level).
- Ki Regen: The character passively regains +1 Ki Energy every 5 rounds.
- May use the Black Remedy ability. Requires 1 Ki Energy.

BLACK REMEDY: All attacks in the next 10 seconds spread a healing remedy. Restores 2d6 Hit Points to allies in a 7-ft. radius.

- 5th level: May use the White Remedy ability. Requires 2 Ki Energy.

WHITE REMEDY: All attacks in the next 10 seconds spread a soothing remedy. All enemies in a 7-ft. radius are slowed for 1 round, and must make a save vs. Death or fall asleep for 5 rounds or until attacked.

- 7th level: May use the Medic Arts ability. Requires 3 Ki Energy.

MEDIC ARTS: Use this ability to select from a list of Medic Arts. The list of abilities includes Lay On Hands, Cure Afflictions, Recall Spirit, Spiritual Clarity, and Poison Weapon. Curative spells are applied instantly to the touched creature.

- 9th level: May use the Healing Rain ability. Requires 4 Ki Energy.

HEALING RAIN: Crystal healing shards rain down in a 12-ft. radius for 2 rounds, washing away fatigue and healing all allied and neutral creatures in the area 10 + 15% of maximum Hit Points each round.

- 13th level: May use the Dragonrot ability. Requires 5 Ki Energy.

DRAGONROT: An illusory dragon spews forth decaying breath. All enemies in a 15-ft. radius are afflicted with Dragonrot, which deals 8 + 5% of max HP damage per round for 5 rounds (no save). Victims also suffer a -4 penalty to Saving Throws for the duration. The effects are not cumulative.

Disadvantages:
- Only gains 8 thieving skill points per level.
- May not use the Stunning Blow ability.
- May not use the Quivering Palm ability.

---

**Noble Scion (Paladin)**

NOBLE SCION: Scion to a respectable line with faith in your pedigree. This holy avenger excels at ranged combat and imbues ammo with blood to fire devastating shots.

Advantages:
- +1 bonus to ranged attack rolls at 1st level, plus an additional +1 bonus every 5 levels.
- May achieve Grand Mastery (5 slots) in longbows, shortbows, crossbows, slings, and darts.
- 3rd level: May use the Blood Bullet ability once per day. Gains additional uses every 3 levels thereafter.

BLOOD BULLET: The character sacrifices 5 Hit Points. For the next 2 rounds, the bonus to ranged THAC0 is doubled, and all ranged attacks deal an extra 1d3 piercing damage for every 3 levels of the character.

- 8th level: +5% chance to score a critical hit with ranged attacks.
- 16th level: +5% chance to score a critical hit with ranged attacks.

Disadvantages:
- May not wear armor heavier than splint mail.
- May not Specialize in melee weapons.
- May not Specialize in any fighting style.

---

</details>

<details>
  <summary>v4.0 kits:</summary>

---

**Full Metal Jaguar (Fighter)**

FULL METAL JAGUAR: A highly capable and versatile warrior, the Full Metal Jaguar leads with a burst of projectiles before leaping in to strike down foes.

Advantages:
- +1 bonus to attack and damage rolls.
- 3rd level: Immune to backstab.
- 5th level: May use the Ghostwalker ability once per day. Gains additional uses every 5 levels thereafter.

GHOSTWALKER: This ability lasts 5 rounds. Once each round, 1 mirror image is created on the character, which can absorb one attack during that round. The number of images created increases to 2 per round at level 10, 3 per round at level 15, and 4 per round at level 20.

- 7th level: Gains the Critical Boost ability (passive).

CRITICAL BOOST: Ranged attacks boost melee critical chance. Each hit with a ranged weapon gives a cumulative +5% bonus for 3 rounds. A critical miss resets the bonus.

Disadvantages:
- May not wear armor heavier than splint mail.

---

**Nurse (Thief)**

NURSE: A born specialist, the Nurse is an adept alchemist, as well as marksman, fit for sleuthing or academia.

Advantages:
- +1 bonus to ranged attack rolls every 3 levels.
- May Specialize (two slots) in shortbows, crossbows, slings, and darts.
- May use the N-Alchemy ability. Gains one use at level 1, one use at level 6, and an additional use every 6 levels thereafter.

N-ALCHEMY: Adds a set of medical tools as special abilities for up to 1 hour. Each requires 1 Alchemy Point, and the character is given 3 points to use. New abilities become available at higher levels:  
&emsp;&emsp;1st level: Medical Darts  
&emsp;&emsp;5th level: First Aid  
&emsp;&emsp;9th level: Overdose  
&emsp;&emsp;13th level: Injection Shot  
&emsp;&emsp;17th level: Autoimmune

MEDICAL DARTS: Equips the character with 5 medical darts, which expire after 5 rounds. These darts will heal allies or deal poison damage to enemies. The amount of healing or damage is equal to 1d4+3, with an extra +1 every 5 levels. Medical Darts strike as +2 weapons with a +5 bonus to THAC0. Proficiency with darts does not affect attack rolls.

FIRST AID: Provide immediate medical care to any living creature. Restores 2 Hit Points per level, up to a maximum of 40 Hit Points.

OVERDOSE: For 5 rounds, the character gains an extra attack per round, +3 per level to all thieving skills, +10% critical hit chance with ranged attacks, and immunity to slow, maze, sleep, stun, and level drain. Overdose may not be used in conjunction with the Haste or Improved Haste spells.

INJECTION SHOT: The next successful ranged attack forces the target to make a save vs. Death at -2 or become feebleminded for 7 rounds. If the Saving Throw is made, the target is confused and slowed for 2 rounds.

AUTOIMMUNE: The recipient is automatically cured of the next instance of poison, disease, hold, paralysis, stun, sleep, blindness, deafness, charm, berserk, fear, confusion, or feeblemind. On activation, the character is also restored 30% of maximum Hit Points. This ability lasts up to 3 turns.

Disadvantages:
- Only gains 15 thieving skill points per level.
- May only wear leather or hide armor.

---

**Spell Fencer (Fighter/Mage)**

SPELL FENCER: This class is an expert duelist, and a natural talent of both weapons and arcane magic.

Advantages:
- May cast one additional spell per level.
- +1 bonus to Armor Class, plus an additional +1 bonus every 5 Fighter levels.
- +1 bonus to Saving Throws vs. Spell every 4 Mage levels, up to a maximum of +5 at level 20.
- Gains the Flash Cast ability (passive). This ability requires 5 levels in Fighter and 5 levels in Mage.

FLASH CAST: With each successful melee attack, the character gains a cumulative +2 bonus to casting speed for 10 seconds. A critical miss resets the bonus.

Disadvantages:
- May not Specialize in ranged weapons.
- May not wear armor heavier than chain mail.

---

</details>

--

Compatibility:
-

**IMPORTANT: If you are running into an issue with the arcane kits (ex. Starjammer) where they don't have the full selection of spells at Level Up or character creation, a current workaround is to install the "No mage school restrictions" tweak from this mod: [Better IWD Pregen](https://github.com/D2-mods/Better-IWD-Pregen/releases). This tweak is safe to install at end of order.**

More info: Due to how the game detects mage specialists, once you get a high enough number of kits, any arcane kits added afterwards will share restricted schools with 1-2 specialists. This only affects the spell selection screen. Mages and bards can still memorize scrolls. This is a problem for Sorcerer kits, however. For now, best thing to do if the issue comes up is to install the tweak mentioned above.


#### General guidelines:
- Install after class revisions, except for Talents of Faerun. If a revision says to install after all kit mods, you can try it both ways. (See ToF notes below)
- Install after new spells or revised spells. (except possibly OlvynSpells, see below)
- Install after new weapons or armor.
- Proficiency overhauls: Can install before or after (except the ToF one). Recommended order is to install this mod before most overhauls, then run the Kit Updater after.
- HLA changes/tweaks: Can install before or after (except the ToF one). All HLA table edits are done from both the main component and the updater. You can re-run the updater at any time to rebuild all HLA tables.

NOTE: I'd recommend to install this mod generally together with other kits, but as the last kit mod, with the possible exceptions of Talents of Faerun and multiclass-focused mods. Technically, this mod is safe to install even after most tweak mods, but it's still a good idea to follow the normal install guidelines, which has kits going before tweaks.

--

#### Spellcasting systems:

Faiths and Powers spheres system:
- Can install before or after FnP (but I'd recommend after).
- See below for additional info.

Deities of Faerun spheres system: 
- Install this mod after DoF.

subtledoctor's 5e casting mod:
- Install this mod before 5e casting.
- Run the Kit Updater after 5e casting.

Sphere lists: [readme-spheres.txt](d2-workshopkits/readme-spheres.txt)

--

**Talents of Faerun notes:**
- Spell components can be installed before or after this mod. I'd recommend to install them before (especially IWD spells).
- Race component can be installed before or after this mod.
- Kit/Tweak components should be installed after this mod. Some are fine installed before, but they are all mixed together, and some need to be installed after, so easier to just install everything after.
- The divine casting kits have full support for custom spheres. Must be installed before the cleric revisions.
- All kits need to be before anything that touches the proficiency or HLA screens (or buttons might not work).

NOTE: Evasion can be installed before or after this mod. Kits that gain Evasion will gain it whether installed before or after. Spells/abilities that allow an Evasion check will only do so if Evasion is already in the game. If you want to install Evasion before this mod, consider using the IWDification version instead.

Kit Updater: **This is REQUIRED for full compat with ToF.** Rebuilds all feats/HLA lists (which will probably be broken without it). Also minor fixes for Medic and Powder Keg kits. More on feats/HLAs below.

--

**OlvynSpells notes (tested with v2.6.0):**
- Spell tweaks can be installed before or after this mod. Some overwrite files, so I'd install them before.
- Paladin/Ranger components can be installed before or after. Note that caster level tweak needs to be after most other kit mods.
- New spells can be installed before or after. Note that these need to be installed after most other kit mods (OlvynSpells adds spells directly to the kit tables for some classes).
- 3e metamagic can be installed before or after (starting with v5.17). Confirmed working with kit-specific arcane/divine spells. ("Spell Level Increase" +2 means using it on a level 2 spell expends one level 4 spell instead).
- Starjammer spells are also compatible with the Necropotence level 9 spell, with or without the spell.ids config option. If installed before OlvynSpells, run the Kit Updater to check EEex effects.

NOTE: With the current versions of both mods, basically everything works fine installed before or after. If you want to be 100% safe, then install new spells after this mod, since future updates could potentially add new EEex effects.

--

**Skills/Feats/HLA mods:**
- Kits that have a disadvantage of not gaining a class ability should generally not take those abilities as feats.
- Some kits may gain certain mod-added HLAs if detected. (note: this mod doesn't install any HLAs, it scans existing HLA tables and copy pastes lines if detected.)
- Crow Hunter can use HLA traps, including mod-added ones (install order doesn't matter). Must be Thief level 14 or higher.

**ToF feats/HLAs:**
- Many kits will have 1 or more additional options. (ex. all archers can take any ranged feat/HLA, Medic can take poison upgrades, Grave Warden can take Use Scrolls/Wands, etc.)
- Some kits have options removed. (ex. Drifter can't take any spell-related feats, but has more combat feats/HLAs than other rangers)
- All arcane kits from this mod will gain one of the "Arcane Knowledge" feats for free. These are required for selecting HLA spells. The feat is denoted at level 1, but effects aren't given until level 18 mage.
- Note: The Kit Updater patches the m_dw_hld.lua file, and backs up an unmodified version in "weidu_external\d2wk" folder. It shouldn't normally be necessary to restore the backup, but just in case, the updater has an option to do so.

#
### FnP additional info:
- The multiclass kits do not require the FnP multiclass mod for compatibility with FnP.
- For best compatibility, install this mod AFTER applying the sphere system.
- It will still work if installed before FnP, but some spheres may be incorrect (will update if it gets fixed).

**FnP multiclass (known issue):**
- Current versions of FnP multiclass hide the F/M/C class from the selection screen. 
- It may possibly be updated to not disable F/M/C, but for now, there are a few ways around this:
1. Install this mod after FnP multiclass. It will automatically re-enable the class.
2. Use cdtweaks/Tweaks Anthology. It has components that make all classes (including FMC) available to all races.
3. Edit clsrcreq.2DA. Just find FIGHTER_MAGE_CLERIC, and set whichever races you want to 1.

**This is how I'd do the install:**
1. FnP spheres, kits, usability
2. The Workshop Kitpack
3. FnP multiclass kits (if using)
4. cdtweaks - enable all classes/multiclasses for all races

**Notes:**
- I used cdtweaks as an example, but any similar race tweak can be used.
- The Kit Updater can now be used to enable the FMC class for half-elves if hidden by a tweak.

---
---

Additional Info (Kit Abilities):
-

**Affected by Wild/Dead Magic:**
- Denial (Grave Warden)  
- Dragonrot (Medic)
- Moonlight Vortex (Moonlight Knight)  
- Force (Temple Knight)  
- Bolt of Glory (Temple Knight)
- Unleash Magic (War Magican)
- Twisted Barricade (War Magican)

**Can be removed by Zone of Sweet Air:**
- Incinerate (Warhound)  
- Dust Explosion (Powder Keg)

**Cures elemental DoT damage (ex. Melf Arrows):**
- Healing Blood (Blood Minister)  
- Healing Rain (Medic)
- Cure Afflictions (Medic)
- Autoimmune (Nurse)

**Removes Grease/Web/Entangle status (on cast or explosion):**
- Hunter Tools (Beast Hunter)
- Twisted Barricade (War Magican)
- Shockwave (Warhound)  
- Incinerate (Warhound)  
- Blasting Song (Powder Keg)
- Dust Explosion (Powder Keg)

#

**Misc kit/effects info:**
- Bleeding effects don't wake sleeping creatures. These effects can be cured by Heal, Regeneration, Lay On Hands, or similar. Stoneskins and Shield of Lathander (or similar mod spells) will protect from bleeding.
- Drifter kit's immunities cover many mod-added spells as well, including the Powder Keg's Dust Explosion (blindness only, it is still invisible in the cloud).
- Nurse's Medical Darts deal double healing or poison damage on a critical hit (target must be vulnerable to crits).
- Shaman Bone Blade's Charm effect lasts only a few rounds, but it can't be broken, except by a Spiritual Clarity (i.e. if you hit it with an AoE spell, it remains charmed).
- The multiclass Cleric kits will gain Holy Symbols at the next Cleric level after 4 million total XP (BG2/EET).
- Kits with armor restrictions can wear 1-2 steps higher for dragon scale armors. (i.e. kits restricted to leather can wear dragon splint)
- All kits from this mod are usable by any race if the base class is usable.

--

**Gain bonus effects from these Beamdog items:**
- Archer's Eyes: Warhound, Noble Scion, Nurse
- Belt of the Skillful Blade: Drifter, Spell Fencer
- Screaming Bagpipes: Powder Keg
- Stalker Gauntlets: Crow Hunter

--

Hunter Badges
-

#### Crafting a Hunter Badge (amulets):
- Certain kits will gain an ability to craft a Hunter Badge, once they reach a certain level.
- These abilities are gained only if a Beast Hunter is also in the party.
- Hunter Badges are usable by anyone, but Beast Hunters gain additional effects.
- Badges can only be crafted once each per playthrough.

NOTE: Beast Hunters don't gain a crafting ability, but they can still purchase these badges.


#### Hunter Badges:
- Spark Hunter Badge
- Radiant Sword Badge
- Cosmic Watcher Badge
- Powder Keg Badge
- Saw Hunter Badge
- Old Hunter Badge

<details>
  <summary>Descriptions</summary>

---

**Spark Hunter Badge**

Hunter badges, of little worth to regular folk, are nonetheless sought after by beast hunters. This badge captures the essence of the darkbeast, whose body is wreathed in destructive energy.

STATISTICS:

Equipped abilities:  
- Armor Class: +1  
- Saving Throws: +1  
- Electricity Resistance: +50%

Special (Beast Hunter):  
- Hunter Tools: Inflicts an extra 1d3 electrical damage

Weight: 1

---

**Radiant Sword Badge**

Hunter badges, of little worth to regular folk, are nonetheless sought after by beast hunters. This badge represents the divine holy blade, an old symbol of beast hunting.

STATISTICS:

Equipped abilities:  
- Armor Class: +1  
- Saving Throws: +1  
- Protection From Evil

Special (Beast Hunter):  
- Hunter Tools: +5 magic damage vs. undead

Weight: 1

---

**Cosmic Watcher Badge**

Hunter badges, of little worth to regular folk, are nonetheless sought after by beast hunters. This badge depicts an eye wide open, gazing always towards the Cosmos.

STATISTICS:

Equipped abilities:  
- Armor Class: +1  
- Saving Throws: +1  
- Magic Resistance: +5%
- Vocalize

Special (Beast Hunter):  
- Hunter Tools: Target is drained 1 level on a failed save vs. Spell at -2

Weight: 1

---

**Powder Keg Badge**

Hunter badges, of little worth to regular folk, are nonetheless sought after by beast hunters. Fire is feared by beasts, and this badge was crafted by a Powder Keg to aid in the hunt.

STATISTICS:

Equipped abilities:  
- Armor Class: +1  
- Saving Throws: +1  
- Fire Resistance: +20%

Special (Beast Hunter):  
- Hunter Tools: 15% chance of an extra 2d12 fire damage

Weight: 1

---

**Saw Hunter Badge**

Hunter badges, of little worth to regular folk, are nonetheless sought after by beast hunters. The saw, with its set of blood-letting teeth, has become a symbol of the hunt.

STATISTICS:

Equipped abilities:
- THAC0: +1
- Armor Class: +1
- Saving Throws: +1

Special (Beast Hunter): 
- Hunter Tools: Target suffers a cumulative -1 penalty to Armor Class for 3 rounds

Weight: 1

---

**Old Hunter Badge**

Hunter badges, of little worth to regular folk, are nonetheless sought after by beast hunters. This badge was a special privilege for the hunters of the past, and should not be dishonored.

STATISTICS:

Equipped abilities:
- Armor Class: +1
- Saving Throws: +1
- Charisma: +2

Special (Beast Hunter): 
- Hunter Tools: +5% chance to score a critical hit, and never roll a critical miss (melee only)

Weight: 1

---

</details>

#### Purchasing the badges:
- BG1/SoD: 3 badge types are obtainable (2 in BG1, all 3 in SoD).
- BG2: All obtainable in SoA. Can purchase additional badges in ToB.
- IWDEE/HoW: Spread throughout + Config option for additional badges in HoW.

--

Starjammer spells:
-

- 1st level: Riftstep
- 2nd level: Steady Current
- 3rd level: Gemini Swap
- 4th level: Pacifying Field
- 5th level: Jolt
- 6th level: Electrocannon
- 7th level: Revitalizer
- 8th level: Riftgate


<details>
  <summary>Descriptions</summary>

---

**Riftstep**  
(Alteration)

Level: 1  
Range: 0  
Duration: Special  
Casting Time: 1  
Area of Effect: The caster  
Saving Throw: None

When Riftstep is cast, a portal opens up in front of the caster, who immediately steps through it. The character may move freely within the rift for 7 seconds while others are frozen in time, but cannot attack, cast spells, or use any items or abilities. After 7 seconds, another portal opens up and the caster steps out of the rift.

A rift should be handled with caution. When this spell is cast, there is a 5% chance to attract the attention of 5 Space Gibberlings, who will savagely attack the caster and <PRO_HISHER> companions.

---

**Steady Current**  
(Evocation)

Level: 2  
Range: 25 ft.  
Duration: 1 round  
Casting Time: 3  
Area of Effect: 2-ft. by 25-ft. beam  
Saving Throw: None

The caster shoots a beam of pure energy that extends to a target, effectively linking the two for one round. The target and any creatures in the path of the beam take 3d6 electrical damage. The spell strikes a second time halfway through its duration, inflicting an additional 3d6 electrical damage. If either the target or the caster moves around, the beam will extend or shrink to maintain the link between the two.

---

**Gemini Swap**  
(Alteration)

Level: 3  
Range: 500 ft.  
Duration: Instant  
Casting Time: 1  
Area of Effect: Special  
Saving Throw: None

The caster selects a target and opens up two Dimension Doors, linked through the Astral Plane, which immediately transfer both target and caster, switching their positions. This spell can be used on both allies and enemies, and the target does not need to be in visual range. As long as the caster knows the target's position on the map, this spell can be cast on it.

---

**Pacifying Field**  
(Abjuration)

Level: 4  
Range: 0  
Duration: 1 turn  
Casting Time: 4  
Area of Effect: 20-ft. radius  
Saving Throw: None

A Pacifying Field covers a 20-ft. radius, centered on the caster. All creatures within the area at the time of casting, whether ally, enemy, or neutral, are enclosed by a protective Sanctuary for one turn. Creatures under a Sanctuary cannot be directly targeted by spells or attacks. There is no Saving Throw and the spell ignores Magic Resistance.

A sanctuaried creature can move around or cast non-attack spells without breaking the spell. Any combat actions, for example, casting a Fireball, a True Sight, or a summoning spell, will remove the Sanctuary.

---

**Jolt**  
(Alteration, Evocation) 

Level: 5  
Range: Special  
Duration: Permanent  
Casting Time: 5  
Area of Effect: 1 party member  
Saving Throw: Special

This spell will restore a fallen creature back to a sliver of health. The target can be of any race and must be a member of the party. To use this spell, cast it on the dead character's portrait.

When cast on a living creature, the spell will cure any form of hold, paralysis, feeblemind, sleep, stun, and intoxication. Any cursed items or effects are also removed.

---

**Electrocannon**  
(Evocation)

Level: 6  
Range: Visual range of the caster  
Duration: Instant  
Casting Time: 6  
Area of Effect: 5-ft. radius  
Saving Throw: 1/2

This spell fires an orb of pure energy at a creature, inflicting 1d4+2 points of electrical damage per level of the caster to the target and any within 5 feet. A 15th level caster, for example, would inflict 15d4+30 damage. Creatures may attempt a save vs. Spell for half damage.

---

**Revitalizer**  
(Necromancy, Evocation)

Level: 7  
Range: Visual range of the caster  
Duration: Permanent  
Casting Time: 1  
Area of Effect: 1 creature  
Saving Throw: None

The caster shoots a golden, pulsating orb at a creature in visual range, restoring 20 + 1d4 Hit Points per level of the caster. A 15th level caster, for example, would restore 20 + 15d4 Hit Points. 

IWD: The spell does not affect creatures without corporeal bodies, those of extraplanar origin, or those not living.

---

**Riftgate**  
(Conjuration/Summoning)

Level: 8  
Range: 30 ft.  
Duration: 1 turn  
Casting Time: 9  
Area of Effect: Special  
Saving Throw: None

By means of this spell, the caster opens a rift in spacetime to a place far beyond the stars. After a moment, a Juggernaut Golem emerges from the rift. The golem stays for 1 turn and will obey the caster as long as it remains summoned. Due to the energy exerted in the summoning process, the caster must wait 1 turn between each use of this spell.

A rift should be handled with caution. When this spell is cast, there is a 2% chance to attract the attention of a balor, who will destroy the golem and exit the rift in its place, intent only on tearing the caster and <PRO_HISHER> companions apart piece by piece. A Protection From Evil spell will not make the fiend ignore the party.

---

</details>

--

Misc items:
- 

- Crowfeather Cloak (cloak)
- Etherbomb Songbook (quick item)
- Ether Booster (amulet)
- Prisoner's Chain (ring)
- Cruciform (amulet)
- Golem Ring (ring)
- Calamity Ring (ring)
- Stone Ring (ring)
- Flynn's Ring (ring)
- Ether Limiter (amulet)

<details>
  <summary>Descriptions</summary>

---

**Crowfeather Cloak (cloak)**

An attire worn by veteran Hunters of Hunters, who dressed as crows to suggest sky burial. The first Hunters came from a foreign land, and gave the dead a virtuous funeral ritual, with the hope that the fallen might find rest in the afterlife.

STATISTICS:

Equipped abilities:  
- Saving Throws: +1
- Hide In Shadows: +30%
- Non-detectable by magical means such as Detect Invisibility and scrying

Special (Crow Hunter):  
- 5% chance of a Visceral Attack (melee only)

Weight: 3

---

**Etherbomb Songbook (item)**

A songbook, said to have fallen out of the sky. The runes on the cover indicate cosmic origins, perhaps a gift left behind by a planar traveler.

STATISTICS:

Charge abilities:  
- Ether Explosion once per day  
  8d8 magic damage in a circle around the user (Save vs. Spell for half)  
  Special: If Lore is 80 or higher, the blast damages only enemies  
  Area of Effect: 15-ft. radius

Special (Powder Keg):  
- Bard Song is changed to Ether Explosion when item ability is used

Weight: 2

---

**Ether Booster (amulet)**

A strange rock discovered in the remains of a fallen meteorite. Can be worn as an amulet to harness the latent magic-enhancing powers.

STATISTICS:

Equipped abilities:  
- All magic and elemental damage inflicted by the wearer is increased by 20%  
- Slows casting speed by 3

Special (War Magician):  
- Unleash Magic: Casting speed penalty is reversed and becomes a +3 bonus

Weight: 1

---

**Prisoner's Chain (ring)**

Portion of a steel chain used to restrain a great hero of old. A prisoner is one who has staked everything on a belief, a proclivity most apparent in the greatest of champions.

STATISTICS:

Equipped abilities:  
- THAC0: +1  
- Armor Class: +1  
- Saving Throws: +1  
- Hit Points: +15  
- Damage Resistance: -10% (all damage types)

Weight: 0

---

**Cruciform (amulet)**

A gem-encrusted stone shaped in the form of a cross. Rather worn from age. The fading blessing grants the wearer a small amount of regeneration.

STATISTICS:

Equipped abilities:  
- Save vs. Death: -2
- Can memorize two extra 2nd-level priest spells
- Regenerate 2 Hit Points per round

Special (Confessor):  
- Bloodletter: Inflicts 3 bleeding wounds at a time

Weight: 1

---

**Golem Ring (ring)**

These enchanted rings were crafted en masse by a Halruaan wizard-inventor. In an instant, the wearer harnesses the raw minerals of the earth, seemingly turning flesh into iron.

STATISTICS:

Equipped abilities:  
- Armor Class: +3  
- Cannot be hasted or slowed

Charge abilities:  
- Iron Flesh three times per day  
  The user's physical resistances are set to 80% and <PRO_HESHE> cannot be pushed or pulled by any force or spell, including a dragon's wing buffet, but movement rate is halved  
  Duration: 4 rounds

Weight: 0

---

**Calamity Ring (ring)**

A ring depicting a dragon's eye, the sign of calamity. This ring exists only in the legends, quietly passed down amongst disciples of dragons.

STATISTICS:

Equipped abilities:  
- Receive double damage from all attacks

Weight: 5

---

**Stone Ring (ring)**

The beloved ring of a forgotten hero. This ring is weighty, and the enchantment carries that weight to the wearer's attacks, strengthening the force of blows.

STATISTICS:

Equipped abilities:
- THAC0: -2

Combat abilities:
- Melee: 15% chance to stun the target 4 seconds
- Ranged: 25% chance to knock back the target

Weight: 3

---

**Flynn's Ring (ring)**

Ring of an eulogized thief, who fought with the wind on his side. Flynn was small of stature, but packed a mighty punch. Strength of wind increases the damage of attacks.

STATISTICS:

Equipped abilities:
- +20% increase to all physical damage dealt when not wearing armor or robes

Weight: 0

---

**Ether Limiter (amulet)**

The stone of this amulet, a meteoric iron, is known to exhibit strong magic and energy-suppressing properties.

STATISTICS:

Equipped abilities:
- Crushing Resistance: +15%
- Magic Damage Resistance: +50%
- Save vs. Spell: +2
- Spellcasting disabled

Special (Warhound):
- Shockwave and Incinerate damage only enemies

Weight: 1

---

</details>

--

**v3.3+ items**
- Gold Scarab (amulet)
- Winged Sword Insignia (ring)
- Red Tearstone Ring (ring)
- Hunter Bone (quick item)
- Jade Feather (amulet)
- Colorless Demon Soul (consumable)
- Shaman Bone Blade (quick item)

<details>
  <summary>Descriptions</summary>

---

**Gold Scarab (amulet)**

This type of amulet takes the form of a sculpted beetle and is typically only found in areas around Mulhorand. The golden scarab increases the amount of experience points obtained from defeating enemies.

STATISTICS:

Equipped abilities:
- +300 bonus XP for each enemy slain by the wearer

Weight: 1

---

**Winged Sword Insignia (ring)**

An honor bestowed upon the most devoted knights, lured into battles of death. The insignia symbolizes the relentless blade, and raises attack power with successive attacks.

STATISTICS:

Combat abilities:
- 33% chance of a cumulative +1 bonus to damage for 2 rounds (melee only)

Weight: 0

---

**Red Tearstone Ring (ring)**

The red tearstone boosts the attack of its wearer when in danger. Once, a goddess mourned the undeserving dead, shedding tears as red as blood. It is said that the stone set in this ring is one such tear.

STATISTICS:

Equipped abilities:
- At under 25% HP, all damage inflicted by the wearer is increased by 40%

Weight: 0

---

**Hunter Bone (quick item)**

The bone of an old hunter whose name is lost. Hold this bone to use the art of Quickening, a technique particular to the first hunters.

STATISTICS:

Charge abilities:
- Blur-Haste three times per day  
  Duration: 20 seconds  
  Area of Effect: The user
  
Weight: 1

---

**Jade Feather (amulet)**

A talisman facsimile of a feather. The jade feather rejects death magic of all forms.

STATISTICS:

Equipped abilities:
- Hit Points: +8
- Immunity to petrification
- Death Ward

Special (Medic):
- 15-ft. radius for Black Remedy and White Remedy effects

Weight: 1

---

**Colorless Demon Soul (consumable)**

The twisted soul of a primeval demon, seeped in strength. Grants the user a large amount of experience, but...

STATISTICS:

Special: +200,000 XP  
Wisdom: -1  
Charisma: -2  
Strength: +1  
Duration: Permanent

Weight: 10

---

**Shaman Bone Blade (quick item)**

A ritual bone blade, coated in a gruesome spinal fluid. Breaks easily, but cuts deep and causes the victim to turn on former allies.

STATISTICS:

Special: Target must make a save vs. Polymorph or be charmed for 4 rounds; if the Saving Throw is made, the target goes berserk for 4 rounds

Weight: 0

---

</details>

#### Non-spoilery item info:
- BG1/SoD: 7 items are obtainable (3 are in SoD). Other items are still installed.
- BG2: All items obtainable in SoA. If starting a new game in ToB, the starting bag will have 1-2 items.
- IWDEE/HoW: Spread throughout, in various dungeons and locations.

--

Caryll Runes
-

#### Info:
- These are usable items with party-wide effects.
- Can be used at will. These items function best gameplay-wise if the player can freely switch between them.
- Characters don't need to be on the same map to be affected.
- Only one rune may be in effect at a time. When a rune is used, it first removes other rune effects.

Note: Icons are slightly different for each rune. They're not amazing looking, but at least helps to differentiate them. The description image is the same for all runes. I couldn't draw anything I liked, so I just used one of the already-made BAM images from BG2.


#### Caryll Runes:
- Clawmark
- Blood Rapture
- Oedon Writhe
- Corruption
- Anti-Clockwise Metamorphosis
- Clockwise Metamorphosis
- Great Lake
- Fading Lake
- Beast's Embrace
- Hunter
- Moon
- Milkweed

<details>
  <summary>Descriptions</summary>

---

**Clawmark**

One of a number of transciptions attributed to the runesmith Caryll, who heard the whispers of the Great Ones and etched them into strange markings. This item applies its effects to all party members.

Only one Caryll Rune may be in effect at a time. Using this rune will remove any previous rune effects.

STATISTICS:

Charge abilities:  
- Clawmark (can be used at will)  
  Area of Effect: The party  
  Duration: 24 hours  
  +5% chance to score a critical hit and critical hits cause bleeding, which inflicts 1d3 damage per round for 4 rounds (no save); a target can be wounded once per round and the effects are cumulative

Weight: 0

---

**Blood Rapture**

One of a number of transciptions attributed to the runesmith Caryll, who heard the whispers of the Great Ones and etched them into strange markings. This item applies its effects to all party members.

Only one Caryll Rune may be in effect at a time. Using this rune will remove any previous rune effects.

STATISTICS:

Charge abilities:  
- Blood Rapture (can be used at will)  
  Area of Effect: The party  
  Duration: 24 hours  
  Critical hits restore 9 Hit Points

Weight: 0

---

**Oedon Writhe**

One of a number of transciptions attributed to the runesmith Caryll, who heard the whispers of the Great Ones and etched them into strange markings. This item applies its effects to all party members.

Only one Caryll Rune may be in effect at a time. Using this rune will remove any previous rune effects.

STATISTICS:

Charge abilities:  
- Oedon Writhe (can be used at will)  
  Area of Effect: The party  
  Duration: 24 hours  
  Critical hits restore 1 memorized spell (up to 6th level)

Weight: 0

---

**Corruption**

One of a number of transciptions attributed to the runesmith Caryll, who heard the whispers of the Great Ones and etched them into strange markings. This item applies its effects to all party members.

Only one Caryll Rune may be in effect at a time. Using this rune will remove any previous rune effects.

STATISTICS:

Charge abilities:  
- Corruption (can be used at will)  
  Area of Effect: The party  
  Duration: 24 hours  
  Regenerate 4 Hit Points per round at under 50% HP, 6 Hit Points per round at under 25% HP, and 8 Hit Points per round at under 10% HP

Weight: 0

---

**Anti-Clockwise Metamorphosis**

One of a number of transciptions attributed to the runesmith Caryll, who heard the whispers of the Great Ones and etched them into strange markings. This item applies its effects to all party members.

Only one Caryll Rune may be in effect at a time. Using this rune will remove any previous rune effects.

STATISTICS:

Charge abilities:  
- Anti-Clockwise Metamorphosis (can be used at will)  
  Area of Effect: The party  
  Duration: 24 hours  
  +4 movement rate; +0.5 Attacks Per Round; -10% to maximum Hit Points

Weight: 0

---

**Clockwise Metamorphosis**

One of a number of transciptions attributed to the runesmith Caryll, who heard the whispers of the Great Ones and etched them into strange markings. This item applies its effects to all party members.

Only one Caryll Rune may be in effect at a time. Using this rune will remove any previous rune effects.

STATISTICS:

Charge abilities:  
- Clockwise Metamorphosis (can be used at will)  
  Area of Effect: The party  
  Duration: 24 hours  
  +20% bonus to maximum Hit Points

Weight: 0

---

**Great Lake**

One of a number of transciptions attributed to the runesmith Caryll, who heard the whispers of the Great Ones and etched them into strange markings. This item applies its effects to all party members.

Only one Caryll Rune may be in effect at a time. Using this rune will remove any previous rune effects.

STATISTICS:

Charge abilities:  
- Great Lake (can be used at will)  
  Area of Effect: The party  
  Duration: 24 hours  
  +10% to all physical damage resistances

Weight: 0

---

**Fading Lake**

One of a number of transciptions attributed to the runesmith Caryll, who heard the whispers of the Great Ones and etched them into strange markings. This item applies its effects to all party members.

Only one Caryll Rune may be in effect at a time. Using this rune will remove any previous rune effects.

STATISTICS:

Charge abilities:  
- Fading Lake (can be used at will)  
  Area of Effect: The party  
  Duration: 24 hours  
  80% Fire Resistance

Weight: 0

---

**Beast's Embrace**

One of a number of transciptions attributed to the runesmith Caryll, who heard the whispers of the Great Ones and etched them into strange markings. This item applies its effects to all party members.

Only one Caryll Rune may be in effect at a time. Using this rune will remove any previous rune effects.

STATISTICS:

Charge abilities:
- Beast's Embrace (can be used at will)  
  Area of Effect: The party  
  Duration: 24 hours  
  Transform into a werewolf during combat; this action happens automatically and the character will revert back to natural form if no enemies are in visual range  
  Special: Clerics and Paladins transform into a greater werewolf

Weight: 0

---

**Hunter**

One of a number of transciptions attributed to the runesmith Caryll, who heard the whispers of the Great Ones and etched them into strange markings. This item applies its effects to all party members.

Only one Caryll Rune may be in effect at a time. Using this rune will remove any previous rune effects.

STATISTICS:

Charge abilities:  
- Hunter (can be used at will)  
  Area of Effect: The party  
  Duration: 24 hours  
  +1 bonus to attack rolls; +5 bonus to all thieving skills

Weight: 0

---

**Moon**

One of a number of transciptions attributed to the runesmith Caryll, who heard the whispers of the Great Ones and etched them into strange markings. This item applies its effects to all party members.

Only one Caryll Rune may be in effect at a time. Using this rune will remove any previous rune effects.

STATISTICS:

Charge abilities:  
- Moon (can be used at will)  
  Area of Effect: The party  
  Duration: 24 hours  
  +65 bonus XP for each enemy slain by the party

Weight: 0

---

**Milkweed**

One of a number of transciptions attributed to the runesmith Caryll, who heard the whispers of the Great Ones and etched them into strange markings. This item applies its effects to all party members.

Only one Caryll Rune may be in effect at a time. Using this rune will remove any previous rune effects.

STATISTICS:

Charge abilities:  
- Milkweed (can be used at will)  
  Area of Effect: The party  
  Duration: 24 hours  
  Transform into a mind flayer during combat, but Wisdom and Constitution are lowered by 2; this action happens automatically and the character will revert back to natural form if no enemies are in visual range

Weight: 0

---

</details>

#### Game notes:
- BG1/SoD: 5 total runes are obtainable (2 are in SoD)
- BG2: All obtainable in SoA portion. Also added to starting bags for some kits in ToB.
- IWDEE/HoW: Spread throughout, in various dungeons and locations.
