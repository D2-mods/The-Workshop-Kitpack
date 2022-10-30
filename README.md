# The Workshop Kitpack

Download: https://github.com/D2-mods/The-Workshop-Kitpack/releases

This is a kitpack I've been working on for a while. It currently has 11 kits—6 warrior, 5 non-warrior. Heavily inspired by FromSoft's Soulsborne games and probably other sources. Also has a few misc items, some with kit-specific effects. Compatible with BGEE, BG2EE, IWDEE, and EET.

NOTE: The abilities tables for these kits are made at install time. Every kit clones the table of the base class (if it exists). This means that any class revisions installed before this mod will be included with these kits.


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

#### Misc stuff
- 1 Holy Symbol     - for the cleric kit  
- 4 Hunter Badges   - can be crafted (see below), can also be purchased  
- 8 new spells      - learned by the Starjammer kit  
- other misc items (all general use items, no weapons or armor)


Components:
-
1. The Workshop Kitpack
2. Misc item pack (Note: Hunter Badges are part of main component)
3. Fix for subtledoctor's 5e casting mod

config.ini: Set a kit to = 0 to prevent install


Kit descriptions:
-

<details>
  <summary>Warrior kits:</summary>

---

**Beast Hunter (Fighter)**

BEAST HUNTER: Whereever there are beasts, there are hunters. Hunters may be protectors or mercenaries, or simply have an addiction for blood and slaughter. This class is particularly adept at combating several powerful types of monsters, including fiends and werewolves.

Advantages:  
- +3 bonus to attack and damage rolls vs. lycanthropes and fiendish creatures.  
- 2nd level: May use the Fire Weapon ability once per day. Gains additional uses every 4 levels thereafter.

FIRE WEAPON: Applies fire element to weapons for 1 turn. All melee attacks inflict an extra 1d3 fire damage for the duration. This ability can be enhanced by equipping special Hunter Badges.

- 5th level: May use the Quicksilver ability once per day. Gains additional uses at levels 9 and 13.

QUICKSILVER: Enhances ranged attacks for 1 turn, adding 2 points of piercing damage and a +5% chance to score a critical hit. All ammo types (arrows, bolts, and bullets) are also enchanted and become able to hit enemies that normally require magical or silver weapons to hit.

Disadvantages:  
- May not wear armor heavier than studded leather.
  
---

**Warhound (Fighter)**

WARHOUND: Warhounds are armored soldiers specializing in long-range warfare. They are often members of elite squadrons, overwhelming enemy armies with a barrage of missiles.

Advantages:  
- +1 bonus to Armor Class vs. missile, plus an additional +1 bonus every 5 levels.  
- +1 to attack and damage rolls with any ranged weapon every 5 levels.  
- May use the Shockwave and Incinerate abilities. Gains one use each at level 4, plus an additional use each every 4 levels, up to a maximum of 5 uses each at level 20.

SHOCKWAVE: The next successful ranged attack explodes in a wave of energy. All creatures in a 15-ft. radius take 2d4 crushing damage and are propelled back a considerable distance (no save). The blast inflicts an additional 2d4 crushing damage every 4 levels thereafter, up to a maximum of 10d4 at level 20.

INCINERATE: The next successful ranged attack expands into a fiery cloud, covering a 15-ft. radius. All creatures in the cloud suffer 1d6 fire damage each round for 4 rounds (Save vs. Breath for half). Damage per round increases by 1d6 every 4 levels thereafter, up to a maximum of 5d6 at level 20.

Disadvantages:  
- May not Specialize in melee weapons.  
- May not Specialize in any fighting style.

---

**Grave Warden (Ranger)**

GRAVE WARDEN: Far to the east, the Grave Wardens tend to the tombs of the slumbering dead, ensuring they remain undisturbed. They are guardians, guides, deterrents, and storytellers, and possess a unique ability to deny death.

Advantages:  
- +4 bonus to Saving Throws vs. Paralysis/Poison/Death.  
- +10 bonus to Lore each level.  
- May cast three arcane spells as priest spells:  
&emsp;1st level: Chromatic Orb.  
&emsp;2nd level: Horror.  
&emsp;3rd level: Skull Trap.
  
- 5th level: May use the Denial ability once per day. Gains additional uses every 5 levels thereafter.

DENIAL: This spell has two effects. First, the recipient becomes immune to all instant death effects for 3 turns. Second, if the recipient falls below 50% of maximum Hit Points, the spell activates and restores the character to full health, consuming the spell in the process.

Disadvantages:  
- May not wear armor heavier than leather.  
- May not use the Charm Animal ability.

---

**Moonlight Knight (Ranger)**

MOONLIGHT KNIGHT: Scholars tell of a decrepit, old dragon that lies atop a high plateau, hidden away from the rest of Toril. The Moonlight Knights, who have gazed upon the forbidden "Other" moon, travel to this place, seeking a revelation from things unseen.

Advantages:  
- +2 bonus to all Saving Throws  
- May be of any alignment.  
- Will not fall due to reputation loss.  
- 2nd level: Gains the Torrent ability (passive).

TORRENT: On a successful melee attack, the character has a 6% chance to become hasted for 10 seconds, gaining an extra attack per round and doubled movement speed. Chance of Haste increases by 1% every 2 levels thereafter, up to a maximum of 15% at level 20.

- 6th level: May use the Moonlight Vortex ability once per day. Gains additional uses at levels 10 and 14.

MOONLIGHT VORTEX: Unleashes a beam of torrential moonlight, which extends as far as the target point, inflicting 4d10 magic damage to enemies in its path. Undead and outerplanar creatures take double damage from this spell. In addition, residual moonlight, left behind from the casting, grants the character a +20% bonus to Magic Resistance for 4 rounds.

Disadvantages:  
- May not Specialize in ranged weapons.  
- May not use stealth.

---

**Confessor (Paladin)**

CONFESSOR: The Confessor is a paladin who acts on behalf of a patron church, being adept at a variety of duties, including, but not limited to, gathering intel, exposing untruths, and hunting down enemies of the church.

Advantages:  
- May cast four arcane spells as priest spells:  
&emsp;1st level: Blindness.  
&emsp;2nd level: Blur.  
&emsp;3rd level: Vampiric Touch.  
&emsp;4th level: Secret Word.

- 2nd level: May use the Rooting Shot ability once per day. Gains additional uses every 4 levels thereafter.

ROOTING SHOT: The next successful ranged attack entangles the target for 3 rounds, plus an additional 3 rounds on a failed save vs. Spell. An entangled creature can still attack, but suffers a -2 penalty to Armor Class and a 20% chance of spell failure.

- 5th level: May use the Bloodletter ability once per day. Gains additional uses at levels 9 and 13.

BLOODLETTER: For 5 rounds, the character is healed 1-4 Hit Points with melee attacks and the target suffers a bleeding wound, which inflicts 1 point of damage per round for 1 turn (no save). A target can be wounded once per round and the effects are cumulative.

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

FORCE: Creates a shockwave. Inflicts no damage, but staggers nearby foes. All enemies within 15 feet are propelled back and stunned for 4 seconds (no save).

- 12th level: May cast Bolt of Glory as a special ability once per day.  
- 16th level: May cast Bolt of Glory as a special ability twice per day.

Disadvantages:  
- May not use missile weapons.  
- May not turn undead.

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

UNLEASH MAGIC: The caster reverses elemental energies. For 4 rounds, each resistance bonus becomes a -10% penalty and the character gains a +10% bonus to all fire, cold, electrical, acid, and magic damage dealt. The bonuses and penalties increase as the caster's innate resistance bonuses increase.

TWISTED BARRICADE: A whirlwind of magical energy envelopes the caster. For 4 rounds, each resistance bonus is tripled and all normal missiles are deflected away harmlessly. While in effect, the character's movement is slowed by half.

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
- May use the Blood Transfusion ability. Gains one use at level 2 and an additional use every 4 levels thereafter. When this ability is used, it opens a submenu with a list of transfusions. New transfusions become available at higher levels.  
&emsp;2nd level: Healing Blood.  
&emsp;6th level: Beast Blood.  
&emsp;10th level: Madman's Blood.  
&emsp;14th level: Lead Elixir.

HEALING BLOOD: Blood drawn from a nun of the Healing Church. Regenerates 2 Hit Points per round for 3 turns. While in effect, the recipient incurs a -1 penalty to attack rolls and damage dealt. This blood will also cure any poisons or diseases.

BEAST BLOOD: Administer medicinal blood that grants temporary Beasthood. The target recieves a +3 bonus to attack and damage rolls, but incurs a -3 penalty to Armor Class. The effects last for 12 hours. This blood will also prevent any poisons or diseases.

MADMAN'S BLOOD: Administer medicinal blood that grants insight into the Cosmos. The target recieves a +5 bonus to Intelligence and Wisdom and a +10% bonus to Magic Resistance, but incurs a -1 penalty to all Saving Throws. The effects last for 12 hours. This blood will also cure level drain.

LEAD ELIXIR: A mysterious concoction that greatly enhances defense at the cost of health. The recipient has all physical damage resistances set to 50%, but incurs a -3 penalty to Constitution. The effects last for 3 turns. This blood will also prevent level drain.

Disadvantages:  
- May not wear gauntlets or bracers.

---

**Crow Hunter (Thief)**

CROW HUNTER: A Crow Hunter acts swiftly and mercilessly against the chosen mark. This is a Hunter of Hunters, an experienced killer, and feared, though not necessarily cruel or evil, despite the unsavoriness of the work.

Advantages:  
- +3 bonus to attack and damage rolls vs. humans, demihumans, and smaller humanoid races.  
- 4th level: May use the Splintering Shot ability once per day. Gains additional uses every 4 levels thereafter.

SPLINTERING SHOT: For 3 rounds, each successful ranged attack bursts into multiple sharp splinters. All enemies in a 15 ft. radius take 2 points of piercing damage and suffer a bleeding wound, which inflicts 1 point of damage per round for 1 turn (no save). A target can be wounded once per round and the effects are cumulative.

- 11th level: May use the Visceral Attack ability once per day. Gains additional uses at levels 15 and 19.

VISCERAL ATTACK: The next melee attack within one round has a 100% chance to score a critical hit. This attack will also restore 20 Hit Points and haste the character for 10 seconds.

Disadvantages:  
- May only distribute 20 skill points per level among thieving skills.  
- May not use the Set Snare ability.

---

**Powder Keg (Bard)**

POWDER KEG: The Powder Kegs are a faction of bards, known for their love of intricate mechanical weapons and big booms. Their instruments double as incendiary devices and may cause a variety of other explosive effects.

Advantages:  
- +20% bonus to Fire Resistance.  
- Gains Bard Songs unique to the Powder Kegs. Songs can be switched between from the special abilities menu. New songs become available at higher levels:  
&emsp;1st level: Blasting Song.  
&emsp;5th level: Booming Song.  
&emsp;10th level: Dust Explosion.  
&emsp;15th level: Frenzying Flame.

BLASTING SONG: A ring of flame bursts outwards in a 15-ft. radius, inflicting 1d4 fire damage per character level to any creatures in the area of effect, up to a maximum of 20d4 at level 20 (Save vs. Breath for half). Only the person playing the song avoids being hit by the flames.

BOOMING SONG: A crushing wave expands outwards in a 15-ft. radius, inflicting 2d4 crushing damage to enemies and causing deafness for 2 rounds, plus an additional 2 rounds on a failed save vs. Spell. Deafness causes a 50% chance to miscast spells.

DUST EXPLOSION: The initial explosion inflicts 5d6 fire damage to enemies in a 15 ft. radius (Save vs. Breath for half). In addition, the blast forms a cloud of dust and smog that lingers for 3 rounds and shrouds a 20 ft. radius. All creatures in the cloud are blinded, but also cannot be directly targeted, unless an attacker can see through invisibility. There is no Saving Throw, though the bard can see clearly within 5 feet.

FRENZYING FLAME: Spreads a frenzy-inducing flame that envelopes a 20-ft. radius and lingers for 2 rounds. Any enemy entering the flames immediately suffers the effects of sleep, confusion, fear, or berserk for 5 rounds (25% chance of each). Enemies also take 2d4 points of magic damage per round while in the area. There is no Saving Throw, though magic resistance can prevent the status effects.

NOTE: If the High-Level Ability "Enhanced Bard Song" is learned, the character will gain an ability to switch to this song.

Disadvantages:  
- Bard Song is unusable for one turn after each use.  
- Only has one quarter the normal Pick Pockets score.

---

</details>


Compatibility:
-

- These aren't hard rules, but compatibility will be best following these.
- Install after Rogue Rebalancing. Several RR files need to be patched for full compatiblity.
- Install after class revision mods, unless they specifically say to install after any kits.
- Install after mods that revise or overwrite spells.

#### Spellcasting systems:
- Compatible with Faiths and Powers spheres system. Can install before or after FnP.
- Compatible with Deities of Faerun spheres system. Install this mod after DoF.
- Compatible with subtledoctor's 5e casting mod. Install this mod before 5e casting.
&emsp;You should also install the extra component related to 5e casting.

#### HLA traps/songs:
- The Crow Hunter and Powder Keg kits need specific handling of HLA traps and songs. 
- Currently, this mod accounts for Rogue Rabalancing hlas.
- If you know of any others, let me know and I can add it.
- Only abilities gained by the base class are relevant for this.

There are no game-breaking errors if a file isn't patched.  
The unpatched HLAs just won't work 100% right with these kits.

---
---

Additional Info (Kit Abilities):
-

- Affected by Wild/Dead Magic zones:  
&emsp;Denial (Grave Warden)  
&emsp;Moonlight Vortex (Moonlight Knight)  
&emsp;Force (Temple Knight)  
&emsp;Bolt of Glory (Temple Knight)

- Can be dispelled:  
&emsp;Denial  
&emsp;Moonlight Vortex (magic resist)  
&emsp;Frenzying Flame (status effects)

- Can be removed by Zone of Sweet Air  
&emsp;Incinerate (Warhound)  
&emsp;Dust Explosion (Powder Keg)

- Blood transfusions will be removed by a Restoration or Greater Restoration.  
- Bleeding effects can be cured by Heal or Greater Restoration, or by the Blood Minister's "Healing Blood".

A few other kit abilities are also spell-like, but I decided not to make them affected by Wild/Dead Magic. It's standard for kit abilities in these games not to be affected. The above abilities are cast like spells so I thought it'd look dumb for them not to be affected by Magic Zones.


Hunter Badges
-

#### Crafting a Hunter Badge (amulets):
- Certain kits will gain an ability to craft a Hunter Badge, once they reach a certain level.
- These abilities are gained only if a Beast Hunter is also in the party.
- Hunter Badges are usable by anyone, but Beast Hunter's gain additional effects.
- Badges can only be crafted once each per playthrough.

NOTE: Beast Hunters don't gain a crafting ability, but they can still purchase these badges.


#### Hunter Badges (amulets):
- Spark Hunter Badge
- Radiant Sword Badge
- Cosmic Watcher Badge
- Powder Keg Badge

<details>
  <summary>Descriptions</summary>

---

**Spark Hunter Badge**

Hunter badges, of little worth to regular folk, are nonetheless sought after by beast hunters. This badge captures the essence of the darkbeast, whose body is wreathed in destructive energy.

STATISTICS:

Equipped abilities:  
- Armor Class: +1  
- Saving Throws: +1  
- Electricity Resistance: 50%

Special (Beast Hunter):  
- Fire Weapon: Inflicts an extra +1d3 electrical damage

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
- Fire Weapon: +5 magic damage vs. undead

Weight: 1

---

**Cosmic Watcher Badge**

Hunter badges, of little worth to regular folk, are nonetheless sought after by beast hunters. This badge depicts an eye wide open, gazing always towards the Cosmos.

STATISTICS:

Equipped abilities:  
- Armor Class: +1  
- Saving Throws: +1  
- Magic Resistance: +10%

Special (Beast Hunter):  
- Fire Weapon: Target is drained 1 level on a failed save vs. Spell

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
- Fire Weapon: 10% chance of an extra +2d12 fire damage

Weight: 1

---

</details>

#### Purchasing the badges:
- Only a couple badges are obtainable in BG1/SoD, and not until reaching the city of Baldur's Gate.
- All badges can be obtained in BG2 and IWD, including additional badges in the expansions.


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

A Pacifying Field covers a 20-ft. radius, centered on the caster. All creatures within the area at the time of casting, whether ally, enemy, or neutral, are enclosed by a protective Sanctuary for one turn. Creatures under a Sanctuary cannot be directly targeted by spells or attacks. There is no Saving Throw and the spell ignores magic resistance.

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

Upon casting this spell, the caster restores a fallen creature back to a sliver of health. The target can be of any race and must be a member of the party. To use this spell, cast it on the dead character's portrait.

Note that the body of the person must be whole, otherwise missing parts are still missing when the person is brought back to life. The person has but 1 Hit Point when raised and must regain the rest by natural healing or curative magic.

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


Misc items:
- 

- Crowfeather Cloak (cloak)
- Etherbomb Songbook (item)
- Ether Booster (amulet)
- Prisoner's Chain (ring)
- Cruciform (amulet)
- Golem Ring (ring)
- Calamity Ring (ring)

<details>
  <summary>Descriptions</summary>

---

**Crowfeather Cloak (cloak)**

An attire worn by veteran Hunters of Hunters, who dressed as crows to suggest sky burial. The first Hunters came from a foreign land, and gave the dead a virtuous funeral ritual, with the hope that the fallen might find rest in the afterlife.

STATISTICS:

Equipped abilities:  
- Saving Throws: +1  
- Hide In Shadows: +15%  
- Move Silently: +15%

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
- Regenerate 2 Hit Points per round

Special (Confessor):  
- Bloodletter: Inflicts 3 bleeding wounds at a time

Weight: 1

---

**Golem Ring (ring)**

These enchanted rings were crafted enmasse by a Halruaan wizard-inventor. In an instant, the wearer harnesses the raw minerals of the earth, seemingly turning flesh into iron.

STATISTICS:

Equipped abilities:  
- Armor Class: +3  
- Cannot be hasted or slowed

Charge abilities:  
- Iron Flesh three times per day  
  The user's physical resistances are set to 80% and <PRO_HESHE> cannot be pushed or pulled by any force or spell, including a dragon's wing buffet, but movement speed is halved  
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

</details>

#### Non-spoilery item info:
- BG1: Only Prisoner's Chain and Calamity Ring are obtainable (though all items are installed).
- SoD: Only Etherbomb Songbook and Golem Ring are obtainable. One of them must be pickpocketed/looted.
- BG2: All items obtainable in SoA portion. If starting a new game in ToB, the starting bag will have 1 or 2 items.
- IWD: Golem Ring is in TotL. The rest are in main IWD campaign. One item must be pickpocketed/looted.
