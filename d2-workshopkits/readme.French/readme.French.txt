The Workshop Kitpack / Les Kits de l'Atelier
GitHub : https://github.com/D2-mods/The-Workshop-Kitpack
Téléchargement : https://github.com/D2-mods/The-Workshop-Kitpack/releases


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

// Kits Multi-classes

- Chasseur (Guerrier / Mage)
- Chasseur (Guerrier / Mage / Clerc)
- Limier (Guerrier / Mage)
- Chevalier au clair de lune (Clerc / Rôdeur)
- Prédateur (Guerrier / Voleur)
- Prédateur (Guerrier / Mage / Voleur)

// Objets Divers
 
- 4 Insignes de Chasseur - peuvent être fabriqués (voir ci-dessous), ou achetés
- 8 Nouveaux sorts - pour le kit du Vagabond des étoiles 
- 9 Runes de Caryll - des objets ayant des effets sur l'ensemble du groupe
- 9 Autres objets - tous des objets utilitaires, pas d'armes ni d'armures

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Composants :

1. The Workshop Kitpack // Les Kits de l'Atelier
2. Pack d'objets divers (Note : Les insignes de chasseur font partie du composant principal.)
3. Correctif / Patch pour le mod 5E_spellcasting de subtledoctor

config.ini: Définir un kit = 0 pour éviter de l'installer
Informations sur les kits  : Voir la page GitHub, les descriptions en jeu, les messages du forum, etc.

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

- Compatible avec le système de sphères de Faiths and Powers. Peut être installé avant ou après.
	- Mes kits multi-classes ne nécessitent pas le mod FnP multiclass pour être compatibles avec Faiths and Powers.
	- Je recommande d'installer ce mod APRÈS FnP multiclass, si vous l'utilisez. Voir les informations ci-dessous.
- Compatible avec le système de sphères de Deities of Faerun. Installez ce mod après DoF.
- Compatible avec le mod 5E_spellcasting de subtledoctor. Peut être installé avant ou après.
	- Mais vous devez installer le composant supplémentaire lié au mod 5E_spellcasting.

Capacités de haut niveau (HLA) Pièges et Chants du barde :

- Les kits Prédateur et Chantre de la poudre nécessitent une manipulation spécifique des pièges et des chansons de haut niveau. 
- Actuellement, ce mod prend en compte les HLAs de Rogue Rebalancing.
- Si vous en connaissez d'autres, faites-le moi savoir et je pourrai les ajouter.
- Seules les capacités acquises par la classe de base sont concernées.

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Problèmes connus : 

FnP multiclass
- La version actuelle de FnP multiclass masque la classe G/M/C (Guerrier / Mage / Clerc) de l'écran de sélection à la création du personnage. 
- Il est possible que le mod FnP multiclass soit mis à jour pour ne pas désactiver la Multi-classe (Guerrier / Mage / Clerc), mais pour l'instant, il existe quelques moyens de contourner ce problème :
1. Installez ce mod après FnP multiclass. Il la réactivera automatiquement.
2. Utilisez cdtweaks/Tweaks Anthology. Il contient des composants qui permettent à toutes les classes (y compris FMC) d'être disponibles pour toutes les races.
3. Éditez le fichier clsrcreq.2DA. Trouvez juste FIGHTER_MAGE_CLERIC, et mettez les races que vous voulez à la valeur 1.

----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------

Version info:

v2.7
- Improved the way mass patching of spells or items is handled (depending on which kits are installed).
- Beast Hunter (multiclass): Wasn't able to equip the "Big Metal Unit" armor (usable by every class/kit). This is fixed.
- Grave Warden: Fixed potential usability issue on non-English installs of BG2EE.

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
