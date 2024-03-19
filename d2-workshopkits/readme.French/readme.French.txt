The Workshop Kitpack / Les Kits de l'Atelier
GitHub : https://github.com/D2-mods/The-Workshop-Kitpack
Téléchargement : https://github.com/D2-mods/The-Workshop-Kitpack/releases
Languages: English, French (JohnBob)


Informations :
- Fortement inspiré par les jeux Soulsborne de FromSoft, mais seuls certains noms, phrases courtes et concepts pour les capacités sont repris directement de ces jeux.

- Les tables de capacités pour ces kits sont créées au moment de l'installation. Chaque kit clone la table de la classe de base (si elle existe). Cela signifie que toute modification de classe installée au préalable sera incluse dans les kits du mod.

- Si des sorts ont été modifiés, alors ils seront appris par certains kits. Par exemple, le kit de l'Exécuteur acquiert normalement Cécité comme un sort de prêtre de niveau 1. Si vous avez installé Spell Revisions au préalable, il obtiendra à la place Obscuring Mist (Brouillard Obscurcissant).

- Ce mod est compatible avec BG:EE, BG2:EE, IWD:EE et EET. Mon intention initiale était de le rendre également compatible avec BG2 classique, mais il est probablement trop tard pour cela. Ce mod fait un usage massif des opcodes exclusifs aux Enhanced Editions.

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Contenu du mod :

// Kits de combattants

- Chasseur (Guerrier)
- Limier (Guerrier)
- Protecteur de sépultures (Rôdeur)
- Chevalier au clair de lune (Rôdeur)
- Exécuteur (Paladin)
- Champion du temple (Paladin)

// Autres kits

- Mage de bataille (Mage)
- Vagabond des étoiles (Ensorceleur)
- Ecclésiaste sanglant (Clerc)
- Prédateur (Voleur)
- Chantre de la poudre (barde)

//v3.0 kits
- Vagabond (rôdeur)
- Chirurgien (moine)
- Seigneur Scion (paladin)

//v4.0 kits
- Full Metal Jaguar (Guerrier)
- Urgentiste (Voleur)
- Dégaineur de sortilège (Guerrier / Mage)

// Kits Multi-classes

- Chasseur (Guerrier / Mage), (Guerrier / Mage / Clerc), (Guerrier / Clerc)
- Limier (Guerrier / Mage)
- Chevalier au clair de lune (Clerc / Rôdeur)
- Prédateur (Guerrier / Voleur), (Guerrier / Mage / Voleur), (Mage / Voleur)
- Full Metal Jaguar (Guerrier / Voleur), (Guerrier / Mage)
- Urgentiste (Mage / Voleur)

// Objets Divers
 
- 6 Insignes de Chasseur - peuvent être fabriqués (voir ci-dessous), ou achetés
- 8 Nouveaux sorts - pour le kit du Vagabond des étoiles 
- 12 Runes de Caryll - des objets ayant des effets sur l'ensemble du groupe
- 17 Autres objets - tous des objets utilitaires, pas d'armes ni d'armures

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Composants :

1. The Workshop Kitpack // Les Kits de l'Atelier
	- Option 1: Kits de base + Kits Multi-classes
	- Option 2: Uniquements les Kits de base
	- Option 3: Pack d'objets divers (Pas de kits ou d'insignes de chasseur)
2. Pack d'objets divers
3. Composant pour le mod 5E_spellcasting de subtledoctor

config.ini: Définir un kit = 0 pour éviter de l'installer

--

Informations supplémentaires :
- Si l'option 1 ou 2 est installée, Alors le composant "Pack d'objets divers" sera proposé séparément.
- Si l'option 3 est installée, les autres composants seront sautés.
- Les insignes de chasseur sont installées en combinaison avec le kit de Chasseur.

Configuration :
- config.ini : Définir un kit = 0 pour éviter de l'installer
- L'Option 2 ignorera toutes les variantes Multi-classes, quels que soient les paramètres de configuration dans le fichier config.ini.

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Création d'insignes de chasseur (amulettes) :

- Certains kits bénéficieront d'une capacité leur permettant de fabriquer un insigne de chasseur, à partir d'un certain niveau.
- Ces capacités ne pourront être acquises que si un Chasseur fait partie du groupe.
- Les insignes de chasseur sont utilisables par tout le monde, mais les Chasseurs bénéficient d'effets spécifiques.
- Les insignes ne peuvent être fabriqués qu'une fois par partie.

REMARQUE : les Chasseurs ne gagnent pas la capacité Création d'une insigne de chasseur, mais ils peuvent néanmoins en acheter.

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Compatibilité :

Instructions générales :

- Installer après Rogue Rebalancing. Plusieurs fichiers de RR doivent être patchés pour une compatibilité totale.
- Installez après les mods qui modifient les classes, à moins qu'il ne soit spécifiquement indiqué d'installer après n'importe quel kit.
- Installer après les mods qui modifient ou écrasent les sorts.
- Installer après les mods qui ajoutent de nouvelles armes ou armures.

Les systèmes de lancement de sorts :

- Compatible avec le système de sphères de Faiths and Powers. Ils peuvent être installé avant ou après.
	- Mes kits multi-classes ne nécessitent pas le mod FnP multiclass pour être compatibles avec Faiths and Powers.
	- Voir les informations ci-dessous.
- Compatible avec le système de sphères de Deities of Faerun. Installez ce mod après DoF.
- Compatible avec le mod 5E_spellcasting de subtledoctor. Peut être installé avant ou après.
	- Installer The Workshop Kitpack avant le mod 5E_spellcasting.
	- Mais vous devez toujours installer le composant supplémentaire lié au mod 5E_spellcasting.

--

Note sur le mod Talents of Faerun : Les composants de sorts peuvent être installés avant ou après The Workshop Kitpack (personnellement, je les installerais avant). Les autres composants doivent être installés après The Workshop Kitpack. Certains pourraient être installés avant, mais le plus simple est de tout installer après.

--

Capacités de haut niveau (HLA) Pièges et Chants du barde :

- v4.7.8 update: Le Prédateur peut désormais utiliser n'importe quel piège HLA (l'ordre d'installation n'a pas d'importance).
- Le Chantre de la poudre est compatible avec les chants de haut niveau du barde (HLA) du mod Rogue Rebalancing (y compris le Chant Persistant). Cela nécessite de patcher les chansons de rr, donc The Workshop Kitpack doit être installé après rr.
- Le Chantre de la poudre peut sélectionner les chants de haut niveau du barde (HLA) du mod Talents of Faerun, mais la capacité spéciale (permettant de changer de chanson) sera remplacée par le chant HLA du jeu original sans mod. De plus, la capacité "Chant Persistant" de ToF fonctionnera avec les autres chants de haut niveau du barde (HLA), mais n'affectera pas les chansons du Chantre de la poudre.
- Le Chantre de la poudre n'est pas testé avec d'autres les chants de haut niveau du barde (HLA) ajoutées par des mods (s'il en existe).

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Information supplémentaire pour FnP :

NOTE : Les kits de Clerc multiclassés ne sont actuellement pas compatible avec la version beta de FnP. Utilisez la version v0.84.5 si vous voulez utiliser ces kits avec Faiths and Powers. 

FnP multiclass :
- La version actuelle de FnP multiclass masque la classe G/M/C (Guerrier / Mage / Clerc) de l'écran de sélection à la création du personnage. 
- Il est possible que le mod FnP multiclass soit mis à jour pour ne pas désactiver la Multi-classe (Guerrier / Mage / Clerc), mais pour l'instant, il existe quelques moyens de contourner ce problème :
1. Installez ce mod après FnP multiclass. Il la réactivera automatiquement.
2. Utilisez cdtweaks/Tweaks Anthology. Il contient des composants qui permettent à toutes les classes (y compris FMC) d'être disponibles pour toutes les races.
3. Éditez le fichier clsrcreq.2DA. Trouvez juste FIGHTER_MAGE_CLERIC, et mettez les races que vous voulez à la valeur 1.

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Version info:

v4.7.9
- French translation updated, thanks to JohnBob.
- Medic: Healing Rain now also removes fatigue.
- Temple Knight: Bolt of Glory no longer applies damage more than once to some creature types.
- Confessor: Blur no longer stacks with itself. Vampiric Touch no longer works on undead or golems.

v4.7.8
- Compatibility fix for EEex (v0.10.0-alpha and later):
	- Some kits had broken effects due to a change in recent EEex versions.
	- All kit abilities are fixed now. The affected kits were the ones with special amulet effects (i.e. Beast Hunter and hunter badges).
	- as a side effect: these item effects will now work even with custom multiclass kits.
- Crow Hunter updates:
	- Damage bonus vs. humans/humanoids now starts at +1, increases to +2 at level 5, and +3 at level 10. For multiclasses, it upgrades with thief level only (not average level of classes).
	- Multiclass variants will now gain Visceral attack at the correct levels (9, 13, and 18).
	- Visceral Attack is now more likely to roll in the upper range of the damage roll. This makes it a little better for mage/thief or single class.
	- Can now use any mod-added traps (i.e. Talents of Faerun HLAs), even if installed after this mod. Must be Thief level 14 or higher.
	- Bonus effect from the Crowfeather Cloak item will now work with custom multiclass kits.
- Other:
	- Beast Hunter: Added an extra effect for the Old Hunter Badge amulet. When using Hunter Tools, the character will never roll a critical miss (with melee attacks).
	- Jade Feather: This now gives a +8 bonus to max HP (basically an extra roll of HP for monks). This replaces the +3 bonus to Save vs. Spell.

v4.7.7
- Fixed a patching error, related to riftstep/riftgate creatures (some equipped effects on their weapons were also added as on-hit effects).
- Fixed a minor variable issue (prevented patching something with bleeding effects).
- Improved patching-related stuff (speed and method), while fixing above issues.
- Minor tweaking of a couple things from last update.

v4.7.6
- New projectiles for these spells: Force (Temple Knight), Electrocannon/Interference (Starjammer), Etherbomb Songbook.
- Powder Keg: for the cloud songs, if effects are decoupled by pausing/unpausing, allies/neutrals should no longer be affected by enemy-only effects (i.e. you can pause/unpause safely inside a Frenzying Flame).
- Starjammer: Riftgate summon now immune to wing buffet (knockback effects), but not to any damage caused by these spells/attacks. Other adjustments to riftstep/riftgate creatures (movement speed, add/remove immunities, etc.).
- Blood Minister: Improved effects structure of Blood Transfusion abilities. Will no longer work on undead, golems, or elementals. If cast on a non-ally, it will now display a string that the "recipient refused the Blood Transfusion", unless the target is naturally immune (will get the normal immunity message).
- Tweaked visuals/sounds for a few other abilities.

v4.7.5
- Powder Keg changes:
	- Reduced delay between each use of a song from 10 rounds to 8 rounds.
	- Blasting Song: Main blast now delayed 1 second (damage unchanged). A new lead-in projectile does an extra 2 fire damage to enemies in a 12-ft. radius. It's visually more interesting now, and the initial projectile lets you know when the main blast is coming.
	- Booming Song: Damage increased from 2d4 to 3d8. Tweaked explosion visual/sound.
	- Dust Explosion: Damage of initial blast increased from 5d6 to 8d6. Creatures immune to blind no longer suffer reduced visual range. Enemies now move at half speed in the cloud.
	- Frenzying Flame: Damage per round increased from 2d4 to 2d12.
- Medic changes:
	- at level 10, Slow Poison is now upgraded to Neutralize Poison.
	- at level 14, Cure Disease is now upgraded to Heal (essentially, the medic's version of "Lay on Hands").
	- at level 18, can now use Lesser Restoration 3 times per day (no fatigue).
	- All medic cures are touch range, applied instantly, have no vocal component, and are not considered spells for wild/dead magic.
	- The spells are otherwise identical to the existing priest spell at the time of install (i.e. in IWDEE, you can't cast Heal on an undead or elemental).
- Other:
	- IWD Evasion: All "Evades effects from..." messages should now say the name of the spell/ability being evaded.
	- New icon for Hunter Tools, recolored icons for Starjammer spells, changed icons for a few other abilities.
	- Blood Minister: if using Spell Revisions, Madman's Blood no longer causes SR fatigue effects.
	- SCS/ToF: Fixed a few wrong ability icons when this mod was installed after SCS/ToF spell tweaks.
	- Other minor changes.

v4.7.4
- Fixed an issue with haste effects if this mod was installed after SCS/ToF spell tweaks. This affected the Moonlight Knight kit and the Hunter Bone item.
- Fixed a mod conflict (with IWDEE Polymorph fixes mod) that would cause characters to learn Psionic Blast permanently, when using the Milkweed rune.
- Switched some item locations around in BG2EE/IWDEE (main change is making Hunter Bone obtainable earlier).
- Added more shaman bone blades in each game (higher quantities and/or obtainable in more locations).
- Starjammer: Pacifying Field, Jolt, and Revitalizer will now ignore immunities to specific spell levels.
- Grave Warden: Denial will now ignore immunities to specific spell levels. (Note that it will still be blocked by immunity to Necromancy school)
- Aethetic fix with Bubb's Spell Menu: The Denial and Moonlight Vortex abilities will now appear as level 1 spells in the special abilities menu (same as all other abilities from this mod).
- Rearranged item text in tra files for better organization.
- Blood Minister: Right-clicking the Blood abilities in the submenu will now show the description for Blood Transfusion. Previously, only the main Blood Transfusion spell would show the description.

v4.7.3
- Golem Ring: Delayed sound effect on item ability was incorrectly set as undispellable.
- Medic: Adjusted visuals for all abilities + fixed color fade effect on White Remedy (was allowing a save).
- Medic: Remedy abilities will no longer affect undead or golems. Healing Rain will still heal any creature, including in IWD (similar to Mist of Eldath). This is the same restriction that's already on Medical Darts and Shaman Bone Blade. Note that this is intentionally less restrictive than IWD rules.
- IWDEE: Grave Warden's Denial ability will now follow IWD cleric rules for the healing effect. The death ward effect can still be cast on any creature. For creatures immune to healing spells in IWD, Denial will last the full 3 turns, unless dispelled or the summon is killed/unsummoned.
- Shaman Bone Blade: Improved effects structure. Will now always play an audio/visual effect, even for immune creatures. Will now display a string that ability was used. Increased cast range from 1 to 3. Elves and half-elves that fail the save against charm, but make the racial check for charm resistance, will now avoid all effects, instead of being berserked.
- Starjammer: Riftgate balor now has a screen shake effect if summoned. Golem attack range increased from 1 to 2, and attacks can now stun on failed save.
- Other minor adjustments or installer improvements.

v4.7.2
- Maintenance:
	- Temple Knight: Slightly reduced knockback strength of Force + added color fade to affected creatures. Stun duration increased internally (it's still roughly 4 seconds, but after the knockback ends).
	- Moonlight Knight: Fixed an inconsistency in the effects of Moonlight Vortex + added lighting effect on allies (only enemies take damage still).
	- Fixed possible minor dialogue weirdness with a chicken.
	- IWDEE: Grave Warden's Skull Trap was giving Evasion check against the wrong spell resource.
- IWD Evasion notes:
	- Took another look at kit abilities that included Evasion checks for IWDEE. These abilities previously allowed Evasion, and no longer do: Shockwave, Moonlight Vortex, Booming Song. These abilities can (still) be evaded: Incinerate, Electrocannon, Steady Current (secondary targets only), Blasting Song, Dust Explosion (initial blast only), Etherbomb Song.
	- BGEE/BG2EE: If Evasion from IWDification or Talents of Faerun is installed before this mod, then the above abilities will also give a check for Evasion in the BGEE games. (components from ToF that just modify class/kit ability tables are fine to install before this mod)

v4.7.1
- Milkweed (rune): Fixed an issue that would occur if spell components from SCS/ToF were installed after this mod. The CON/WIS drain wasn't being removed right away after battle (it wears off itself eventually).
- Note that recommended install order is still this mod after the spell components, but in case the opposite order is used, Milkweed rune should now be compatible either way.
- Since I was editing this anyways, using a Caryll Rune will no longer instantly remove the stat drain from Milkweed. It gets removed automatically at the same time that the polymorph is reversed.

v4.7
- Maintenance:
	- Fixed Denial/Revitalizer abilities if installed after SCS/ToF revisions to 'cure wounds' spells.
	- IWDEE: item files no longer have description images (fixes visual glitch with Infinity UI++).
	- Standardized and reworked internally how armor restrictions are handled for kits.
	- Improved installer speed.
	- Updated ADD_KIT_EX to v0.6.2.
	- Updated description for Drifter kit to note support for ToF Evasion.
	- Spell selection fix (compatibility section) now links to 'Subtled Spell Tweaks'.
- Adjustments:
	- Starjammer: Riftgate golem is now immune to spells that instakill summons.
	- Starjammer: Riftgate balor will now leave after reloading the area, instead of staying forever.
	- Medic: Healing Rain now heals 3d8+2 per round (increased from 13.5 to 15.5 average).


v4.6
- Fixed abilities for imported multiclass kits (BG2/ToB/SoD):
	- Imported characters will no longer be missing abilities when starting a new game.
	- This issue affected Charname only, though the fix is applied for all characters.
- Alignment changes:
	- Drifter: Can be any non-lawful alignment.
	- Grave Warden: Any non-evil, non-chaotic alignment.
- Nurse kit update:
	- Medical Darts: Now does base 1d4+3 healing/damage, with another +1 every 5 levels.
	- Medical Darts: Increased number of darts given per use from 8 to 10.
	- Medical Darts: Added a hidden +15 THAC0 bonus when targeting allies.
	- Injection Shot: Increased time to make the shot from 2 rounds to 5 rounds.
	- Injection Shot: Feeblemind duration reduced from permanent to 8 hours.
- Crow Hunter update:
	- Visceral Attack: Now gained at levels 9, 13, and 18 (was previously at 11, 15, and 19).
	- Multiclass fix: Imported characters will no longer gain Set Snares, not even if you export/import a CHR repeatedly.
- War Magician update:
	- Unleash Magic: Now also gives a +2 caster level bonus (no longer useless at low levels).
	- Twisted Barricade: At level 10+, this will also deflect single target spells while active.
	- Both abilities are now dispellable.
	- Both abilities are now affected by wild/dead magic zones.
- Compatibility update for DoF mod:
	- Added an additional minor sphere for each Paladin/Ranger kit. This is mainly for QoL. 
	- Every kit will, at minimum, have either "Healing" or "Combat" sphere as a minor sphere.
- Other:
	- Installer improvements.
	- Updated ADD_KIT_EX to v0.6.0.


v4.5
- Medical Darts (Nurse kit):
	- Will no longer inflict bleed on allies if Clawmark rune is used. Enemies can still be affected.
	- Critical hits will deal double healing or poison damage. Target must be vulnerable to crits.
- Other:
	- Installer improvements.
	- Changed BAM icons for holy symbols again.
- Compatibility:
	- Fixed some weirdness when installed before OlvynSpells mod.
	- Note that unlike most kit mods, this mod can be installed before or after OlvynSpells.

v4.4
- Fixes:
	- EET: Fixed an incorrect text string (Injection Shot ability).
	- Confessor: Fixed entangle effect not being dispellable.
	- Shaman Bone Blade: Fixed incorrect weight in description.
	- EE Fixpack: Fixed immunity spell states on items/effects (opcode 328 needs to be set to IWD2 mode).
- Kit changes:
	- Drifter: Can gain IWDEE Evasion if ability is in the game (IWDEE and IWDification versions supported).
	- Nurse: Can now Specialize in ranged weapons.
	- Grave Warden: Becomes immune to fear at level 3 and immune to blindness/gaze attacks at level 8.
	- Confessor: Entangle now ignores magic resist. It still has a saving throw after 3 rounds, and can still be dispelled.
- Ability notes:
	- Spells/items that block death magic will also block Aec'Letec's death gaze in BG1/EET.
	- Reduced casting time: Denial, Moonlight Vortex, Medical Darts.
	- Passive abilities will give a message in the dialogue box when initially gained at level up.
- Compatibility notes:
	- Faiths and Powers beta (v0.85sd20): Improved compatibility. Notably, the paladin kits will be able to select any of the 3 archetypes, whether this mod is installed before or after FnP. Previously, the archetype selection gave an undefined string if this mod was installed after FnP.
	- 5e-casting: Updated compatibility info to say that this mod should be installed before 5e-casting. Spellcasting will work either way, but the Cruciform item needs to be installed before the item update component of 5e-casting.

v4.3
- Main component now has 3 subcomponents:
	- Option 1: Base kits + multiclass variants
	- Option 2: Base kits only
	- Option 3: Misc items only (no kits or Hunter Badges)
- Additional info:
	- If you install kits here, the item pack is still a separate component afterwards.
	- If you install the item pack here, kits cannot be installed later.
- Other:
	- Made it a bit easier to find one of the items (for all games). It's an intentionally hidden item, but you can get it through dialogue now, instead of killing or stealing.
	- Other minor changes.

v4.2
- IWDEE notes:
	- If the Misc items component is installed, an NPC in Kuldahar will now give a hint for where some of the items from this mod become available.
	- Moved a couple items that were in the main game to HoW (including 1 Hunter Badge).
	- Added a Colorless Demon Soul to the main game. So now 2 are obtainable (the other in TotLM).
	- More Shaman Bone Blade locations.
	- Can no longer purchase additional Hunter Badges in HoW (see note below).
- Other:
	- Shaman Bone Blade: Saving throw changed to a Save vs. Polymorph.
	- Adjusted a few item icons.
	- BG1/BG2: Changed location for 1-2 Hunter Badges in each game.
- Note on Hunter Badge availability in Throne of Bhaal or Heart of Winter:
	- This is now a config.ini option, instead of always installed.
	- Enables adding additional Hunter Badges to merchants in ToB or HoW.
	- By default, this is ON for ToB and OFF for HoW.

v4.1
- Added 2 consumable/limited use items:
	- Colorless Demon Soul
	- Shaman Bone Blade
- Adjusted bleeding effects again:
	- Bloodletter (Confessor): 2 damage per round for 6 rounds
	- Splintering Shot (Crow Hunter): 1 damage per round for 1 turn
	- Clawmark (rune): 1d3 damage per round for 4 rounds
- Medic kit changes:
	- Removed restriction: May not wear gauntlets or bracers.
	- Added restriction: May not use bladed weapons, other than short swords or daggers.
- Other:
	- Hunter Bone: AC/saves bonuses no longer stack. Changed BAM images (previous BAM files now used for Shaman Bone Blade).
	- Golem Ring: Added sound effect when Iron Flesh duration ends.

v4.0
- Split install into 2 subcomponents:
	- Option 1: Base kits + multiclass variants
	- Option 2: Base kits only
- New kits:
	- Full Metal Jaguar (fighter)
	- Nurse (thief)
	- Spell Fencer (fighter/mage)
- New multiclass variants:
	- Beast Hunter FC
	- Crow Hunter MT
	- Full Metal Jaguar (FM, FT)
	- Nurse MT
- Fixes:
	- Fixed a possible install error, related to config settings.
	- Spelling fixes.
- Kit updates:
	- Moonlight Knight: Moonlight Vortex will now always do some damage to undead and outerplanar creatures. Magic resist, for these creatures, will halve the damage instead of negating it.
	- Confessor: The saving throw for Rooting Shot was previously checked immediately on-hit. It will now be checked after the initial 3 rounds of entangle. The effects are still the same.
- Other changes:
	- Moved a few item locations.
	- Other minor changes (sounds, icons, kit colors, etc.)
	- Added Config option for Holy Symbols in IWDEE (disabled by default)

v3.3
- New items:
	- Added 5 items to the "Misc items" component. Obtainable in BG2 and IWD/HoW.
	- One of the new items, Jade Feather, enhances the Medic's remedy abilities.
- Kit Changes:
	- Medic: Increased Healing Rain area to 12-ft. radius.
	- Drifter: The first bonus to hit/damage is now gained at level 3, then every 5 levels thereafter.
- Other Changes:
	- Hunter (rune): Added +5 to all thieving skills (in addition to +1 THAC0 bonus)
	- Changed icons for some abilities.

v3.2
- Fixes:
	- Grave Warden: Fixed usability issue (wasn't able to wear Montolio's Cloak in BG2).
	- Drifter: Record screen will no longer show a line for Backstab (just a visual fix).
- Kit changes:
	- Warhound: The first bonus to hit/damage is now gained at level 3, then every 5 levels thereafter (so 3, 8, 13, 18, etc.).
	- Confessor: Increased healing (1d4+1) and reduced bleed duration (8 rounds) for Bloodletter.
	- Medic: Increased healing (2d6) for Black Remedy.
	- Crow Hunter: Reduced bleed duration (6 rounds) for Splintering Shot.
	- Beast Hunter: Revised Hunter Tools. Reduced duration for Quicksilver.
	- Blood Minister: Tweaked/revised all blood types.
- Item changes:
	- Clawmark (rune): Bleed duration reduced from 10 rounds to 4 rounds.
	- Moon (rune): Increased XP bonus from +35 to +65 per kill.
	- Powder Keg Badge: Increased chance of fire damage from 10% to 15%.

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

Translation/Coding Assistance:

JohnBob - French Translation

subtledoctor - coding assistance for compatibility with his mods

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
- 7-Zip (https://www.7-zip.org/)

Original game resources included with this mod belong to the rights holders.
These files are packaged with the mod to account for possible missing files.
