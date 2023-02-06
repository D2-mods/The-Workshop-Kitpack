# The Workshop Kitpack / Les Kits de l'Atelier

Téléchargement : https://github.com/D2-mods/The-Workshop-Kitpack/releases  
Forum : [Beamdog](https://forums.beamdog.com/discussion/86749/mod-the-workshop-kitpack), [Gibberlings3](https://www.gibberlings3.net/forums/topic/36122-the-workshop-kitpack/)

C'est un pack de Kits sur lequel je travaille depuis un moment. Il comporte actuellement 11 kits - 6 combattants, 5 non-combattants + des déclinaisons pour multi-classes. Il contient également plus de 20 objets, dont 4 insignes de Chasseur, 9 Runes de Caryll et 9 autres objets divers. Fortement inspiré par les jeux Soulsborne de FromSoft et probablement d'autres sources. Ce mod est compatible avec BG:EE, BG2:EE, IWD:EE et EET.

NOTE : Les tables de capacités pour ces kits sont créées au moment de l'installation. Chaque kit clone la table de la classe de base (si elle existe). Cela signifie que toute modification de classe installée au préalable sera incluse dans les kits du mod.


Contenu du mod :
-

#### [Kits de combattants](https://github.com/D2-mods/The-Workshop-Kitpack/blob/main/README.French.md#descriptions-des-kits-)

- Chasseur (Guerrier)
- Limier (Guerrier)
- Protecteur de sépultures (Rôdeur)
- Chevalier au clair de lune (Rôdeur)
- Exécuteur (Paladin)
- Champion du temple (Paladin)

#### [Autres kits](https://github.com/D2-mods/The-Workshop-Kitpack/blob/main/README.French.md#descriptions-des-kits-)

- Mage de bataille (Mage)
- Vagabond des étoiles (Ensorceleur)
- Ecclésiaste sanglant (Clerc)
- Prédateur (Voleur)
- Chantre de la poudre (barde)

#### Kits Multi-classes

- Chasseur (Guerrier / Mage)
- Chasseur (Guerrier / Mage / Clerc)
- Limier (Guerrier / Mage)
- Chevalier au clair de lune (Clerc / Rôdeur)
- Prédateur (Guerrier / Voleur)
- Prédateur (Guerrier / Mage / Voleur)

#### Objets Divers
  
- 6 [Insignes de Chasseur](https://github.com/D2-mods/The-Workshop-Kitpack/blob/main/README.French.md#insignes-de-chasseur) &emsp;-&emsp;&emsp; peuvent être fabriqués (voir ci-dessous), ou achetés
- 8 [Nouveaux sorts](https://github.com/D2-mods/The-Workshop-Kitpack/blob/main/README.French.md#sorts-du-vagabond-des-%C3%A9toiles-) &emsp;&emsp;&emsp;-&emsp;&emsp; pour le kit du Vagabond des étoiles 
- 12 [Runes de Caryll](https://github.com/D2-mods/The-Workshop-Kitpack/blob/main/README.French.md#les-runes-de-caryll) &emsp;&emsp;-&emsp;&emsp; des objets ayant des effets sur l'ensemble du groupe
- 10 [Autres objets](https://github.com/D2-mods/The-Workshop-Kitpack/blob/main/README.French.md#objets-divers-) &emsp; &emsp;-&emsp;&emsp; tous des objets utilitaires, pas d'armes ni d'armures


Composants :
-

1. The Workshop Kitpack // Les Kits de l'Atelier
2. Pack d'objets divers (Note : Les insignes de chasseur font partie du composant principal.)
3. Correctif pour le mod 5E_spellcasting de subtledoctor

config.ini: Définir un kit = 0 pour éviter de l'installer


Descriptions des Kits :
-

<details>
  <summary>Kits de combattants :</summary>

---

**Chasseur (Guerrier)**

CHASSEUR : Quand il y a des bêtes, il y a des chasseurs. Ceux-ci peuvent être des gardiens, des protecteurs ou bien des mercenaires et des bouchers excités par le sang et les massacres. Cette classe est tout particulièrement apte à combattre de multiples monstres et autres créatures puissantes, notamment les démons et les loups-garous.

Avantages :
- Bonus de 3 aux jets d'attaque et de dégâts contre les lycanthropes et les démons.
- 2ème niveau : Peut utiliser la capacité « Coup de feu » une fois par jour, puis une fois supplémentaire tous les 4 niveaux.

COUP DE FEU : Le Chasseur peut enflammer ses armes, pendant 1 tour toutes les attaques de mêlée infligent 1d3 dégâts de feu supplémentaires. Cette capacité peut être améliorée en équipant des insignes spécifiquement destinés au Chasseur.

- 5ème niveau : Peut utiliser la capacité « Projectile d'argent » une fois par jour, puis une fois supplémentaire au niveaux 9 et 13.

PROJECTILE D'ARGENT : Pendant 1 tour toutes les attaques à distance sont amplifiées, infligeant 2 points de dégâts perforants supplémentaires, elles bénéficient également de 5 % de chances de réaliser un coup critique. Tous les types de munitions (flèches, carreaux et billes) sont également enchantés, devenant ainsi capables de toucher les ennemis nécessitant des armes magiques ou en argent.

Inconvénients : 
- Ne peut pas porter d'armure plus lourde que la besantine.
  
---

**Limier (Guerrier**

LIMIER : Les Limiers sont des soldats cuirassés spécialisés dans les combats à distance. Ils sont souvent membres d'escadrons d'élite, submergeant les armées ennemies avec un déluge de projectiles.

Avantages :
- Bonus de 1 à la classe d'armure contre les projectiles au niveau 1 et un bonus supplémentaire tout les 4 niveaux.
- Bonus de 1 aux jets d'attaque et de dégâts avec les armes à distance tout les 5 niveaux.
- Peut atteindre la grande maîtrise (5 points de compétence) avec les arcs long, les arcs courts, les arbalètes, les frondes et les fléchettes.
- Peut utiliser les capacités « Onde de choc » et « Incinération » au niveau 4, puis une fois supplémentaire tous les 4 niveaux, jusqu'à un maximum de 5 au niveau 20

ONDE DE CHOC : La prochaine attaque à distance réussie provoque une vague d'énergie. Toutes les créatures situées dans un rayon de 4,5 m subissent 2d4 points de dégâts contondants et sont projetées en arrière sur une distance considérable, sans jet de sauvegarde possible. La déflagration inflige 2d4 points de dégâts contondants supplémentaires par tranche de 4 niveaux, jusqu'à un maximum de 10d4 points de dégâts au niveau 20.

INCINÉRATION : La prochaine attaque à distance réussie s'étend telle une nuée ardente, recouvrant un rayon de 4,5 mètres. Toutes les créatures présentes dans le nuage subissent 1d6 points de dégâts de feu à chaque round pendant 4 rounds (un jet de sauvegarde contre les souffles réduit les dégâts de moitié). Les dégâts par round augmentent de 1d6 points par tranche de 4 niveaux, jusqu'à un maximum de 5d6 points de dégâts au niveau 20.

Inconvénients : 
- Ne peut se spécialiser avec les armes de mêlés.
- Ne peut se spécialiser dans aucun des styles de combat.

---

**Protecteur de sépultures (Rôdeur)**

PROTECTEUR DE SÉPULTURES : Loin à l'est, les Protecteur de sépultures veillent sur les tombes et le sommeil des morts, s'assurant qu'ils reposent en paix. Ils sont des gardiens, des guides et des conteurs, et possèdent la faculté de renier la mort.

Avantages :
- Bonus de 4 aux jets de sauvegarde contre la paralysie, la mort et les poisons.
- Bonus de 10 au score de connaissances tout les 4 niveaux.
- Peut lancer trois sort profane à la manière d'un prêtre :  
  1er niveau : « Orbe chromatique ».  
  2ème niveau : « Horreur ».  
  3ème niveau : « Piège à crânes ».
  
- 5ème niveau : Peut utiliser la capacité « Dénégation » une fois par jour, puis une fois supplémentaire tous les 5 niveaux.

DÉNÉGATION : Ce sort a deux effets. Tout d'abord, la cible devient immunisé, pendant 3 tours, à tous les effets provoquant une mort instantanée. 
Ensuite, si celle-ci voit ses points de vie tomber en dessous des 50 %, le deuxième effet du sort s'activera et lui redonnera toute sa santé, consumant le sort au cours du processus.

Inconvénients : 
- Ne peut pas porter d'armure plus lourde que l'armure de cuir.
- Ne peut utiliser la capacité « Charme-animal ».

---

**Chevalier au clair de lune (Rôdeur)**

CHEVALIER AU CLAIR DE LUNE : Les érudits parlent d'un vieux dragon sur le déclin qui se trouve au sommet d'une montagne, à l'écart du reste de Toril. Les chevaliers au clair de lune, qui ont bravé l'interdit et contemplé cette "autre" lune, se rendent en ce lieu, en quête d'une illumination sur les mystères de l'invisible.

Avantages :
- Bonus de 2 aux jets de sauvegarde.
- Peut être de n'importe quel alignement.
- Ne peut être déchu en raison de sa réputation.
- 2ème niveau : Gagne la capacité passive « Cascade ».

CASCADE : Une attaque de mêlée réussie octroie au personnage 6 % de chances de bénéficier des effets de la hâte pendant 10 secondes, gagnant une attaque supplémentaire par round et doublant sa vitesse de déplacement. La probabilité augmente de 1 % par tranche de 2 niveaux, jusqu'à un maximum de 15 % au niveau 20..

- 6ème niveau : Peut utiliser la capacité « Albédo » une fois par jour, puis une fois supplémentaire au niveaux 10 et 14.

ALBÉDO : Libère un rayonnement lunaire dévastateur qui s'étend jusqu'à la zone ciblée, infligeant sur son passage 4d10 points de dégâts magiques aux ennemis. Les morts-vivants et les créatures extra-planaires subissent le double des dégâts. De plus, la lumière rémanente issue de l'incantation confère au personnage un bonus de 20 % de résistance magique, pendant 4 rounds.

Inconvénients : 
- Ne peut se spécialiser avec les armes à distance.
- Ne peut pas utiliser la Furtivité.

---

**Exécuteur (Paladin)**

EXÉCUTEUR : L'Exécuteur est un paladin qui œuvre pour son église. Il est doué d'une grande variété de compétences, rechercher des informations, dévoiler les mensonges et traquer les ennemis de l'église ne sont que quelques unes des tâches qui lui sont confiées.

Avantages :
- Peut lancer quatre sort profane à la manière d'un prêtre :  
  1er niveau : « Cécité ».  
  2ème niveau : « Flou ».  
  3ème niveau : « Toucher vampirique ».  
  4ème niveau : « Mot secret ».

- 2ème niveau : Peut utiliser la capacité « Empalement » une fois par jour, puis une fois supplémentaire tous les 4 niveaux.

EMPALEMENT : La prochaine attaque à distance réussie enchevêtre la cible pendant 3 rounds, plus 3 rounds supplémentaires en cas d'échec du jet de sauvegarde contre les sorts. Une créature enchevêtrée a toujours la possibilité d'attaquer, mais elle subit une pénalité de 2 à sa classe d'armure et a 20 % de chances d'échouer l'incantation de ses sorts.

- 5ème niveau : Peut utiliser la capacité « Évangile sanguinolente » une fois par jour, puis une fois supplémentaire au niveaux 9 et 13.

ÉVANGILE SANGUINOLENTE : Pendant 5 rounds, le personnage récupère 1 à 4 points de vie grâce aux attaques de mêlée et provoque une hémorragie à sa cible, lui infligeant 1 point de dégâts par round pendant 1 tour (sans jet de sauvegarde possible). Une même créature peut être blessée une fois par round et les effets sont cumulatifs.

Inconvénients : 
- Ne peut pas porter d'armure plus lourde que la besantine.
- Ne peut utiliser « Imposition des mains »

---

**Champion du temple (Paladin)**

CHAMPION DU TEMPLE : Ces chevaliers en armure lourde sont principalement présents près des temples et des églises de Toril, protégeant ces lieux sacrés. Ce sont des soldats vertueux, qui se dressent avec détermination contre tout adversaire.

Avantages :
- Peut atteindre la haute maîtrise (4 points de compétence) avec les armes d'hast et les armes contondantes.
- Peut utiliser la capacité « Imposition des mains » trois fois par jour.
- 2ème niveau : Peut utiliser la capacité « Force » une fois par jour, puis une fois supplémentaire tous les 4 niveaux.

FORCE : Produit une onde de choc qui n'inflige aucun dégât, mais étourdit les ennemis à proximité. Tous les adversaires présents dans un rayon de 4,5 mètres sont propulsés en arrière et étourdis pendant 4 secondes (sans jet de sauvegarde possible).

- 12ème niveau : Peut utiliser la capacité « Rayon divin » une fois par jour.
- 16ème niveau : Peut utiliser la capacité « Rayon divin » deux fois par jour.

Inconvénients : 
- Ne peut pas utiliser les armes à projectiles.
- Ne peut pas repousser les morts-vivants.~
@100604 = ~Déchu : Champion du temple

---

</details>

<details>
  <summary>Autres kits :</summary>

---

**Mage de bataille (Mage)**

MAGE DE BATAILLE : Le Mage de bataille apprend à puiser dans ses capacités magiques naturelles et à les amplifier, lui permettant ainsi d'acquérir des aptitudes supérieures à celles d'un magicien ordinaire, bien que ce processus soit physiquement très éprouvant.

Avantages :
- Bénéficie de 10 % de résistance contre les dégâts de feu, de froid, d’électricité, d'acide et magique. Gagne 5 % supplémentaires tous les 5 niveaux, jusqu'à un maximum de 30 % au niveau 20.
- Peut utiliser les capacités « Déchaînement de magie » et « Barricade », Gagne une utilisation supplémentaire au niveau 2, puis tous les 4 niveaux.

DÉCHAÎNEMENT DE MAGIE : Le lanceur de sorts renverse les énergies élémentaires. Pendant 4 rounds, chaque bonus devient une pénalité de 10 % et le lanceur gagne 10 % à tous les dégâts de feu, de froid, d'électricité, d'acide et de magie qu'il inflige. Ces bonus et pénalités augmentent au même rythme que la résistance naturelle du Mage de bataille.

BARRICADE : Un tourbillon d'énergie magique enveloppe le lanceur de sorts. Pendant 4 rounds, tous ses bonus de résistance sont triplés et tous les projectiles normaux sont déviés. Pendant la durée du sort, les mouvement du personnage sont ralentis de moitié.

Inconvénients :
- Pénalité de 2 en Force et en Constitution.

---

**Vagabond des étoiles (Ensorceleur)**

VAGABOND DES ÉTOILES : Les Vagabonds des étoiles sont des nomades venus de par delà les étoiles. Ils ont fui un immense fléau sévissant sur leur planète d'origine, et plusieurs d'entre eux se sont retrouvés sur Toril. Ces marginaux ressemblent à de puissants sorciers, mais la destruction de leur foyer, et la dérive qui en a résulté, a eu des répercussions considérables sur leur mental et leur physique.

Avantages :
- Ne peut être affecté par la magie empêchant les incantations, Surdité et Silence
- Accède immédiatement aux sorts de niveau 1 à 8 dédiés au Vagabond des étoiles : « Faille », « Surcharge », « Dipôle », « Pacification », « Défibrillation », « Bombe électrique », « Grog », et « Fissure ».
- 5ème niveau : Peut utiliser la capacité « Interférence » une fois par jour, puis une fois supplémentaire tous les 5 niveaux.

INTERFÉRENCE : Perturbe les attaques de projectiles et les sorts dans la zone d'effet. Tous les ennemis dans un rayon de 9 m subissent une pénalité de 3 aux jets d'attaque avec les armes à distance et leurs sorts ont 25 % de chances d'échouer pendant 1 tour (pas de jet de sauvegarde). Les pénalités augmentent de 1 pour les jets d'attaque et de 5 % pour l'échec des sorts tous les 5 niveaux.

Inconvénients : 
- Pénalité de 2 à la Dextérité et en Sagesse.

---

**Ecclésiaste sanglant (Clerc)**

ECCLÉSIASTE SANGLANT : L'ancienne Église de la Guérison aujourd'hui entaché d'hérésie était le foyer du rétablissement par le sang, un remède dont on prétendait qu'il avait la capacité de guérir n'importe quelle maladie, qu'elle soit d'origine naturelle ou divine. Depuis quelque temps, des prêtres de cette église ont recommencé à apparaître sur la Côte des Épées.

Avantages :
- Immunité au drainage de niveau, aux poisons et aux maladies..
- Peut utiliser la capacité « Injection » une fois par jour à partir du niveau 2, puis une fois supplémentaire tous les 4 niveaux. Lorsque cette capacité est activée, elle permet d'utiliser plusieurs type de transfusions. De nouvelles transfusions sont disponibles en fonction du niveau :  
  2ème niveau : « Guérison par le sang ».  
  6ème niveau : « Sang de la Bête ».  
  10ème niveau : « Sang du lunatique ».  
  14ème niveau : « Élixir sanglant ».

GUÉRISON PAR LE SANG : Du sang prélevé sur une des sœurs de l'Église de la Guérison permet de régénérer 2 points de vie par round pendant 3 tours. Dans ce laps de temps, le bénéficiaire subit une pénalité de 1 aux jets d'attaque et de dégâts. Ce sang guérit également les empoisonnements et les maladies.

SANG DE LA BÊTE : Administrez ce sang confère temporairement les aptitudes d'une bête. La cible bénéficie d'un bonus de 3 aux jets d'attaque et de dégâts, mais subit une pénalité de 3 à la classe d'armure. Les effets durent 12 heures. Ce sang protège également contre les poisons et les maladies.

SANG DU LUNATIQUE : Cette injection donne un léger aperçu du cosmos et de ses mystères. La cible bénéficie d'un bonus de 5 à l'intelligence et à la sagesse, ainsi qu'un bonus de 10 % de résistance à la magie, mais elle subit aussi une pénalité de 1 à tous ses jets de sauvegarde. Les effets durent 12 heures. Ce sang restaure également les niveaux perdus.

ÉLIXIR SANGLANT : Une décoction mystérieuse qui améliore considérablement la résistance au détriment de la santé. Le destinataire voit toutes sa résistance à tous les dégâts physiques fixées à 50 %, mais subit aussi une pénalité de 3 à la Constitution. Les effets durent 3 tours. Ce sang prévient également le drainage de niveau.

Inconvénients : 
- Ne peut porter de gantelets ou de bracelets.

---

**Prédateur (Voleur)**

PRÉDATEUR : Agissant avec célérité et sans aucune pitié pour sa cible. Ce Prédateur de prédateurs est un tueur expérimenté et redouté, mais il n'est pas nécessairement cruel ou maléfique, malgré le caractère déplaisant de son travail.

Avantages :
- Bonus de 3 bonus aux jets d'attaque et de dégâts contre les humains, les demi-humains, et autres races humanoïdes de petites taille.
- 4ème niveau : Peut utiliser la capacité « Tir éclatant » une fois par jour, puis une fois supplémentaire tous les 4 niveaux.

TIR ÉCLATANT : Pendant 3 rounds, chaque attaque à distance réussie génère de multiples éclats tranchants. Tous les ennemis dans un rayon de 4,5 m subissent 2 points de dégâts perforants et souffrent d'hémorragie, ce qui leur inflige 1 point de dégâts supplémentaires par round pendant 1 tour (pas de jet de sauvegarde). Une même cible peut être blessée une fois par round et les effets sont cumulatifs.

- 11ème niveau : Peut utiliser la capacité « Instinct » une fois par jour, puis une fois supplémentaire au niveaux 15 et 19.

INSTINCT : La prochaine attaque de mêlée, dans un délai d'un round, a 100 % de chances de réussir un coup critique. Cette capacité restaure également 20 points de vie à l'utilisateur et le place sous l'effet de la hâte pendant 10 secondes.

Inconvénients : 
- Ne dispose que de 20 points par niveau pour les talents de voleur.

---

**Chantre de la poudre (barde)**

CHANTRE DE LA POUDRE : Les Chantres de la poudre sont une faction de bardes, connus pour leur amour des armes mécaniques complexes et des grosses explosions. Leurs instruments font office de dispositifs incendiaires et peuvent provoquer une variété d'effets explosifs.

Avantages :
- Bénéficie de 20 % de résistance au feu.
- Accède à un chant du barde spécifique au Chantre de la poudre. Les chansons peuvent être sélectionnées à partir du menu des capacités spéciales. De nouvelles chansons sont disponibles en fonction du niveau :  
  1er niveau : « Chant enflammé ».  
  5ème niveau : « Son détonant ».  
  10ème niveau : « Déflagration de poussière ».  
  15ème niveau : « Flamme frénétique ».

CHANT ENFLAMMÉ : Un cercle de flammes se propage sur un rayon de 4,5 m, infligeant 1d4 points de dégâts de feu par niveau du personnage, jusqu'à un maximum de 20d4 au niveau 20, toute créature se trouvant dans la zone d'effet doit réussir un jet de sauvegarde contre les souffles pour réduire les dégâts de moitié. Seule la personne qui joue la chanson est à l'abri des flammes.

SON DÉTONANT : Une vague massive se propage sur un rayon de 4,5 m, infligeant 2d4 points de dégâts contondants aux ennemis qui se retrouve sous l'effet de la surdité pendant 4 rounds, un jet de sauvegarde contre les sorts réduit ce temps de moitié. La surdité entraîne une probabilité d’échec de l'incantation des sorts de 50 %.

DÉFLAGRATION DE POUSSIÈRE : La première déflagration inflige 5d6 points de dégâts de feu à tous les ennemis dans un rayon de 4,5 m (un jet de sauvegarde contre les souffles réduit les dégâts de moitié.). Le nuage de poussière et la fumée que dégage l'explosion persiste pendant 3 rounds et s'étant sur une surface de 6 mètres de rayon. Toutes les créatures présentes dans le nuage sont aveuglées sans jet de sauvegarde possible, mais elles sont aussi dissimulées par la fumée et ne peuvent être directement visées, à moins d'avoir les moyens de percevoir ce qui est invisible.

FLAMME FRÉNÉTIQUE : Cette attaque répand une flamme vivante qui enveloppe un rayon de 6 m et persiste pendant 2 rounds. Tout ennemi pénétrant dans les flammes subit immédiatement les effets du sommeil, de la confusion, de la peur ou de la folie du berserker pendant 5 rounds (25 % de chances d'être affecté par chacun). Les ennemis subissent également 2d4 points de dégâts magiques par round tant qu'ils se trouvent dans la zone. Il n'y a pas de jet de sauvegarde, mais la résistance à la magie peut contrecarrer les effets.

REMARQUE : Si la capacité de haut niveau « Chant du barde amélioré » est acquise, le personnage disposera d'une capacité lui permettant de basculer sur cette chanson.

Inconvénients : 
- Le chant du barde est inutilisable pendant un tour après chaque usage.
- N'obtient qu'un quart du score de Vol à la tire.

---

</details>


Compatibilité :
-

**IMPORTANT : Si vous rencontrez un problème avec les kits de magie des arcanes (par exemple le Vagabond des étoiles), qui ne disposeraient pas de la sélection complète de sorts prévu lors de la montée de niveau ou à la création du personnage, une solution de contournement consiste à installer le composant "No Opposition Schools" (Pas d’écoles d'opposition) du mod [Tome & Blood](https://github.com/subtledoctor/TomeAndBlood/releases). Cette modification peut être installée en toute sécurité à la fin de votre installation.**

Informations supplémentaires : En raison de la façon dont le jeu détecte les mages spécialistes, une fois que vous atteignez un nombre suffisamment élevé de kits, tous les kits de mage ajoutés par la suite sont susceptibles de partager des restrictions avec un ou plusieurs mages spécialisés. Cela n'affecte que l'écran de sélection des sorts. Les Mages et les Bardes pourront toujours mémoriser des parchemins. C'est principalement un problème pour les kits d'ensorceleurs. Pour l'instant, la meilleure chose à faire si le problème se pose est d'installer le composant TnB mentionné ci-dessus.


#### Instructions générales :

- Installer après Rogue Rebalancing. Plusieurs fichiers de RR doivent être patchés pour une compatibilité totale.
- Installez après les mods qui modifient les classes, à moins qu'il ne soit spécifiquement indiqué d'installer après n'importe quel kit.
- Installer après les mods qui modifient ou écrasent les sorts.
- Installer après les mods qui ajoutent de nouvelles armes ou armures.

#### Les systèmes de lancement de sorts :

- Compatible avec le système de sphères de Faiths and Powers. Peut être installé avant ou après.
	- Mes kits multi-classes ne nécessitent pas le mod FnP multiclass pour être compatibles avec Faiths and Powers.
	- Je recommande d'installer ce mod APRÈS FnP multiclass, si vous l'utilisez. Voir les informations ci-dessous.
- Compatible avec le système de sphères de Deities of Faerun. Installez ce mod après DoF.
- Compatible avec le mod 5E_spellcasting de subtledoctor. Peut être installé avant ou après.
	- Mais vous devez installer le composant supplémentaire lié au mod 5E_spellcasting.

#### Capacités de haut niveau (HLA) Pièges et Chants du barde :

- Les kits Prédateur et Chantre de la poudre nécessitent une manipulation spécifique des pièges et des chansons de haut niveau. 
- Actuellement, ce mod prend en compte les HLAs de Rogue Rebalancing.
- Si vous en connaissez d'autres, faites-le moi savoir et je pourrai les ajouter.
- Seules les capacités acquises par la classe de base sont concernées.

#### Problèmes connus : 

 FnP multiclass
- La version actuelle de FnP multiclass masque la classe G/M/C (Guerrier / Mage / Clerc) de l'écran de sélection à la création du personnage. 
- Il est possible que le mod FnP multiclass soit mis à jour pour ne pas désactiver la Multi-classe (Guerrier / Mage / Clerc), mais pour l'instant, il existe quelques moyens de contourner ce problème :
1. Installez ce mod après FnP multiclass. Il la réactivera automatiquement.
2. Utilisez cdtweaks/Tweaks Anthology. Il contient des composants qui permettent à toutes les classes (y compris FMC) d'être disponibles pour toutes les races.
3. Éditez le fichier clsrcreq.2DA. Trouvez juste FIGHTER_MAGE_CLERIC, et mettez les races que vous voulez à la valeur 1.

---
---

Informations additionnelles (Les capacités des kits) :
-

- Affecté par les zones sans magie ou d'entropie :  
	- "Dénégation" (Protecteur de sépultures)  
	- "Albédo" (Chevalier au clair de lune)  
	- "Force" (Champion du temple)  
	- "Rayon divin" (Champion du temple)

- Peut être dissipé :  
	- "Dénégation"  
	- "Albédo" (résistance à la magie)  
	- "Empalement" (Protection contre les effets d’enchevêtrement) (Exécuteur)
	- "Flamme frénétique" (Protection contre les effets) (Chantre de la poudre)

- Peut être dissipé par le sort Zone d'air pur :  
	- "Incinération" (Limier)  
	- "Déflagration de poussière" (Chantre de la poudre)

- Autres :  
	- "Injection" sera retiré par un sort de "Restauration" ou de "Restauration majeure". (Ecclésiaste sanglant)
	- Les hémorragies peuvent être soignés par "Soins", "Restauration majeure", ou par "Guérison par le sang" de l'Ecclésiaste sanglant.
	- Les kits de clerc multi-classes obtiendront leur symbole sacré lorsqu'il atteindrons 4 million XP (BG2EE / EET)

D'autres capacités sont aussi des sorts, mais j'ai décidé qu'elles ne seraient pas affectées par les zones sans magie ou d'entropie. C'est la norme, de ne pas être affectées, pour les capacités de kit dans le jeux. Les capacités ci-dessus sont utilisées comme des sorts, donc j'ai pensé que cela aurait l'air idiot qu'elles ne soient pas affectées par les zones sans magie ou d'entropie.


Insignes de Chasseur
-

#### Création d'insignes de chasseur (amulettes) :

- Certains kits bénéficieront d'une capacité leur permettant de fabriquer un insigne de chasseur, à partir d'un certain niveau.
- Ces capacités ne pourront être acquises que si un Chasseur fait partie du groupe.
- Les insignes de chasseur sont utilisables par tout le monde, mais les Chasseurs bénéficient d'effets spécifiques.
- Les insignes ne peuvent être fabriqués qu'une fois par partie.

REMARQUE : les Chasseurs ne gagnent pas la capacité Création d'une insigne de chasseur, mais ils peuvent néanmoins en acheter.


#### Les différents Insignes de Chasseur :

- Insigne Étincelant
- Insigne de l'Épée radieuse
- Insigne du Veilleur
- Insigne du Chantre de la poudre
- Insigne de la Scie
- Insigne du Vétéran

<details>
  <summary>Descriptions</summary>

---

**Insigne Étincelant**

Les insignes de Chasseur ont peu de valeur pour les gens ordinaires, mais sont néanmoins très convoités par les Chasseurs. Cet insigne a capturé l'essence d'une des Sombrebêtes, dont le corps est enveloppé d'énergie électrique destructrice.

PARAMÈTRES :

Capacités d'équipement : 
- Classe d'armure : +1
- Jets de sauvegarde : +1
- Résistance à l’électricité : +50 %

Spécial (Chasseur): 
- Coup de feu : Inflige 1d3 points de dégâts électriques supplémentaires.

Poids : 1

---

**Insigne de l'Épée radieuse**

Les insignes de Chasseur ont peu de valeur pour les gens ordinaires, mais sont néanmoins très convoités par les Chasseurs. Cet insigne représente la divine Lame sainte, un ancien symbole pour la chasse aux monstres.

PARAMÈTRES :

Capacités d'équipement : 
- Classe d'armure : +1
- Jets de sauvegarde : +1
- Protection contre le mal

Spécial (Chasseur): 
- Coup de feu : Inflige 5 points de dégâts magiques supplémentaires contre les morts-vivants.

Poids : 1

---

**Insigne du Veilleur**

Les insignes de Chasseur ont peu de valeur pour les gens ordinaires, mais sont néanmoins très convoités par les Chasseurs. Cet insigne représente un œil écarquillé, fixant sans cesse les étoiles.

PARAMÈTRES :

Capacités d'équipement : 
- Classe d'armure : +1
- Jets de sauvegarde : +1
- Résistance à la magie : +10 %

Spécial (Chasseur): 
- Coup de feu : Draine un niveau à la cible, en cas d'échec à son jet de sauvegarde contre les sorts à -2.

Poids : 1

---

**Insigne du Chantre de la poudre**

Les insignes de Chasseur ont peu de valeur pour les gens ordinaires, mais sont néanmoins très convoités par les Chasseurs. Le feu est redouté par toutes les créatures, cet insigne a été fabriqué par un Chantre de la poudre afin de contribuer à la chasse.

PARAMÈTRES :

Capacités d'équipement : 
- Classe d'armure : +1
- Jets de sauvegarde : +1
- Résistance au feu : +20 %

Spécial (Chasseur): 
- Coup de feu : 10 % de chance d'infliger 2d12 dégâts de feu supplémentaires.

Poids : 1

---

**Insigne de la Scie**

Les insignes de Chasseur ont peu de valeur pour les gens ordinaires, mais sont néanmoins très convoités par les Chasseurs. La scie et ses dents effilées capables de faire couler le sang est devenue un symbole de la chasse.

PARAMÈTRES :

Capacités de charge :
– TAC0 : Bonus de 1
– Classe d'armure : Bonus de 1
– Jets de sauvegarde : Bonus de 1

Spécial (Chasseur): 
– Coup de feu : La cible subit une pénalité cumulative de 1 à la classe d'armure pendant 3 rounds

Poids : 1

---

**Insigne du Vétéran**

Les insignes de Chasseur ont peu de valeur pour les gens ordinaires, mais sont néanmoins très convoités par les Chasseurs. This badge was a special privilege for the hunters of the past, and should not be dishonored.

PARAMÈTRES :

Capacités de charge :
– Classe d'armure : Bonus de 1
– Jets de sauvegarde : Bonus de 1
– Charisme : Bonus de 2

Spécial (Chasseur): 
– Coup de feu : +5 % de chance d’effectuer un coup critique

Poids : 1

---

</details>

#### Acquérir les insignes :

- BGEE : 2 insignes peuvent être récupérés, mais pas avant d'avoir atteint la ville de la Porte de Baldur.
- SoD : Les 2 insignes de BG1, plus 1 insigne additionnelle peuvent être récupérés.
- Tous les insignes peuvent être récupérés dans BG2EE et IWDEE, y compris des insignes supplémentaires dans les extensions.


Sorts du Vagabond des étoiles :
-

- 1er niveau : Faille
- 2ème niveau : Surcharge
- 3ème niveau : Dipôle
- 4ème niveau : Pacification
- 5ème niveau : Défibrillation
- 6ème niveau : Bombe électrique
- 7ème niveau : Grog
- 8ème niveau : Fissure


<details>
  <summary>Descriptions</summary>

---

**Faille**  
(Altération)

- Niveau : 1
- Portée : 0
- Durée : Spécial
- Temps d'incantation : 1
- Zone d'effet : Personnelle
- Jet de sauvegarde : Aucun

« Faille » permet d'ouvrir un portail devant le lanceur de sorts, qui le traverse immédiatement, celui-ci peut alors se déplacer librement dans la faille pendant 7 secondes tandis que les autres sont figés dans le temps. Le personnage ne peut ni attaquer, ni lancer de sorts ou encore utiliser des objets et autres capacités. Après 7 secondes, un autre portail s'ouvre et le lanceur de sorts retourne à la réalité.

Une faille doit être manipulée avec prudence. Lorsque ce sort est lancé, il a 5 % de chances d'attirer l'attention de 5 Gobelins de l'espace, qui attaqueront sauvagement le lanceur et ses compagnons.

---

**Surcharge**  
(Évocation)

- Niveau : 2
- Portée : 7,5 m.
- Durée : 1 round
- Temps d'incantation : 3
- Zone d'effet : faisceau de 60 cm sur 7,5 m.
- Jet de sauvegarde : Aucun

Le lanceur de sorts projette un faisceau d'énergie pure qui s'étend jusqu'à sa cible, liant les deux pendant un round. La cible et toutes les créatures se trouvant sur la trajectoire du rayon subissent 3d6 points de dégâts d'électricité. Le sort émet une seconde impulsion au milieu de sa durée, infligeant 3d6 points de dégâts électriques supplémentaires. Si la cible ou le lanceur de sorts se déplacent, le rayon s'étend ou rétrécit de manière à maintenir le lien entre les deux.

---

**Dipôle**  
(Altération)

- Niveau : 3
- Portée : 150 m.
- Durée : Instantané
- Temps d'incantation : 1
- Zone d'effet : Spécial
- Jet de sauvegarde : Aucun

Le lanceur de sorts choisit une cible et déploie deux portes dimensionnelles, reliées par le plan astral, qui permutent immédiatement leurs positions. Ce sort peut être jeté sur des alliés comme sur des ennemis, et la cible n'a pas besoin d'être à portée de vue. Tant que le lanceur a connaissance de sa position sur la carte, celle-ci peut être atteinte.

---

**Pacification**  
(Abjuration)

- Niveau : 4
- Portée : 0
- Durée : 1 tour
- Temps d'incantation : 4
- Zone d'effet : 6 m de rayon
- Jet de sauvegarde : Aucun

Un champ apaisant couvre un rayon de 6 mètres, centré sur le lanceur de sorts. Toutes les créatures se trouvant dans la zone d'effet au moment de l'incantation, qu'elles soient alliées, ennemies ou même neutres, sont enveloppées dans un sanctuaire pendant un tour. Les créatures touchés ne peuvent plus être directement ciblées par des sorts ou des attaques. Aucun jet de sauvegarde n'est possible et ce sort ignore la résistance à la magie.

Une créature sous l'effet d'un sanctuaire peut se déplacer librement ou lancer des sorts non offensifs sans rompre le sortilège. Mais toute action potentiellement agressive, comme une boule de feu, la vision véritable ou une invocation, fait disparaître le sanctuaire.

---

**Défibrillation**  
(Altération, Évocation) 

- Niveau : 5
- Portée : Spécial
- Durée : Permanent 
- Temps d'incantation : 5
- Zone d'effet : 1 membre du groupe
- Jet de sauvegarde : Spécial

Ce sort ramène à la vie une créature tombée au combat. La cible peut être de n'importe quelle race, mais doit être membre du groupe.

Si ce sort est lancé sur une créature vivante, il guérit l'immobilisation, la paralysie, la débilité mental, le sommeil, l'étourdissement et l'intoxication. Toute malédiction ou objet maudit est également retiré.

---

**Bombe électrique**  
(Évocation)

- Niveau : 6
- Portée : Champ visuel du lanceur
- Durée : Instantané
- Temps d'incantation : 6
- Zone d'effet : Rayon de 1,5 m
- Jet de sauvegarde : 1/2 dégâts

Ce sort envoie un orbe d'énergie pure en direction d'une créature, infligeant à la cible 1d4+2 points de dégâts d'électricité par niveau du lanceur de sorts, ainsi qu'à toute personne se trouvant dans un rayon de 1,5 mètre. Un lanceur de sorts de 15ème niveau infligera donc 15d4+30 points de dégâts. Les créatures qui réussissent un jet de sauvegarde contre le sort ne subissent que la moitié des dégâts.

---

**Grog**  
(Nécromancie, Évocation)

- Niveau : 7
- Portée : Champ visuel du lanceur
- Durée : Permanent
- Temps d'incantation : 1
- Zone d'effet : 1 créature
- Jet de sauvegarde : Aucun

Le lanceur de sorts projette un orbe doré et palpitant sur une créature à portée de vue, lui restituant 20 + 1d4 points de vie par niveau du lanceur de sorts. Un lanceur de sorts de 15ème niveau restaurera donc 20 + 15d4 points de vie à la cible.

---

**Fissure**  
(Conjuration, Invocation)

- Niveau : 8
- Portée : 9 m.
- Durée : 1 tour
- Temps d'incantation : 9
- Zone d'effet : Spécial
- Jet de sauvegarde : Aucun

Grâce à ce sort, le lanceur ouvre une fissure à travers l'espace-temps pour atteindre un endroit situé bien au-delà des étoiles. Après un certain temps, un golem géant émerge de la fissure. Celui-ci reste présent pendant un tour et obéit au lanceur de sorts pendant la durée de l'invocation. En raison de l'énergie déployée dans le processus, le lanceur de sorts doit patienter 1 tour entre chaque utilisation.

Une faille doit être manipulée avec précaution. Lorsque ce sort est lancé, il a 2 % de chances d'attirer l'attention d'un balor, qui détruira le golem et pénétrera dans notre monde à sa place avec un unique dessein, mettre en pièces le lanceur de sorts et ses compagnons. Un sort de protection contre le mal ne protégera pas le groupe contre ce démon.

---

</details>


Objets divers :
- 

- Manteau de plumes de corbeau (cape)
- Livre de chants, le souffle de l'Éther (objet)
- Amulette de l'Éther (amulette)
- Chaîne du prisonnier (anneau)
- Croix (amulette)
- Anneau du golem)
- Anneau de calamité
- Anneau de pierre
- Anneau de Flynn
- Atténuateur d'Éther (amulette)

<details>
  <summary>Descriptions</summary>

---

**Manteau de plumes de corbeau (cape)**

Une tenue portée par les plus anciens des Prédateurs, ces vétérans se déguisaient en corbeaux pour symboliser l'envole d'une âme vers le ciel. Les premiers Prédateurs venaient d'une terre inconnue et pratiquaient avec vertu un rituel funéraire pour les les défunts, dans l'espoir qu'ils puissent trouver le repos dans l'au-delà.

PARAMÈTRES :

Capacités d'équipement :
- Jets de sauvegarde : +1
- Se cacher dans l'ombre : +30 %
- Indétectable par des moyens magiques tels que « Détection de l'invisibilité » et par la scrutation

Spécial (Prédateur):
- 5 % de chance de déclencher la capacité « Instinct » (seulement avec les attaques de mêlée)

Poids : 3

---

**Livre de chants, le souffle de l'Éther (objet)**

La rumeur raconte que ce livre de chants serait tombé du ciel. Les runes qui ornent la couverture évoquent des origines extra-planaire, peut-être un présent laissé par un voyageur venu d'un autre univers.

PARAMÈTRES :

Capacités de charge :
- Expulsion d'Éther une fois par jour
Inflige 8d8 points de dégâts magiques autour de l'utilisateur (jet de sauvegarde contre les sorts pour réduire de moitié).
Spécial : Si le score de connaissances est égal ou supérieur à 80, le souffle n'endommage que les ennemis.
Zone d'effet : rayon de 4,5 m.

Spécial (Chantre de la poudre): 
- Le Chant du barde est remplacé par Expulsion d'Éther lorsque la capacité de l'objet est activée.

Poids : 2

---

**Amulette de l'Éther**

Une roche étrange découverte parmi les débris d'une météorite. Elle peut être portée comme une amulette pour exploiter ses pouvoirs latents.

PARAMÈTRES :

Capacités d'équipement :
- Tous les dégâts magiques et élémentaires infligés par le porteur augmentent de 20 %.
- Pénalité : Temps d'incantation augmenté de 3 

Spécial (Mage de bataille): 
- Déchaînement de magie : Inverse la pénalité au temps d'incantation qui devient un bonus, Temps d'incantation réduit de 3.

Poids : 1

---

**Chaîne du prisonnier (anneau)**

Fragment d'une chaîne en acier, jadis utilisée pour entraver un puissant héros. Un prisonnier est quelqu'un qui a tout risqué pour ses convictions, une attitude que l'on retrouve principalement chez les plus grands champions.

PARAMÈTRES :

Capacités d'équipement :
- TAC0 : +1
- Classe d'armure : +1
- Jets de sauvegarde : +1
- Points de vie : +15
- Résistance aux dégâts : Bonus de 10 % (contre tous les types de dégâts)

Poids : 0

---

**Croix (amulette)**

Une pierre en forme de croix incrustée de pierres précieuses. Usée par le temps, elle accorde au porteur une capacité de régénération limité.

PARAMÈTRES :

Capacités d'équipement :
- Jet de sauvegarde contre la mort : Bonus de 2
- Peut mémoriser 2 sorts divins supplémentaires de niveau 2
- Régénère 2 points de vie par round

Spécial (Exécuteur): 
- Évangile sanguinolente : Inflige 3 points de dégâts d'hémorragie

Poids : 1

---

**Anneau du golem**

Ces anneaux enchantés ont été fabriqués en masse par un sorcier et inventeur d'Halruaa. Il suffit de le porter pour exploiter les minéraux naturels contenus dans la terre et apparemment être capable de transformer la chair en fer.

PARAMÈTRES :

Capacités d'équipement :
- Classe d'armure : +3
- La vitesse de déplacement du porteur ne peut être modifier

Capacités de charge :
- Peau de fer, trois fois par jour
- Durée : 4 rounds

La résistance physique de l'utilisateur est fixée à 80 %, il ne peut plus être repoussé ou attiré par aucune force ni aucun sort, y compris les coups d'ailes de dragon, mais en contrepartie sa vitesse de déplacement est réduite de moitié.


Poids : 0

---

**Anneau de calamité**

Cette anneau représente un œil de dragon, un signe de calamité. Son existence n'est contenue que dans les légendes, transmises secrètement par les disciples du dragons.

PARAMÈTRES :

Capacités d'équipement :
- Double les dégâts à chaque attaque

Poids : 5

---

**Anneau de pierre**

Le bijou bien-aimé d'un héros oublié. Cet anneau pèse lourd, et son enchantement répercute ce poids sur les attaques du porteur, renforçant la violence des coups.

PARAMÈTRES :

Capacités d'équipement :
- TAC0 : Bonus de 2

Capacités de combat :
- Mêlée : 15 % de chance d'étourdir la cible pendant 4 secondes
- Distance : 25 % de chance de projeter et renverser la cible 

Poids : 3

---

**Anneau de Flynn**

L'anneau d'un voleur glorieux, qui a combattu avec le vent en poupe. Flynn était de petite stature, mais il avait un crochet puissant. La force du vent augmente les dégâts.

PARAMÈTRES :

Capacités d'équipement :
- Inflige 20 % de dégâts physiques supplémentaires lorsque vous ne portez pas d'armure ou de robe.

Poids : 0

---

**Atténuateur d'Éther (amulette)**

La pierre de cette amulette, provenant d'une météorite, est connue pour présenter de puissantes propriétés magiques, elle est aussi capable d'atténuer les effets de l'énergie.

PARAMÈTRES :

Capacités de charge :
– Résistance aux dégâts contondants : +15 %
– Résistance aux dégâts magiques : +50 %
– Jets de sauvegarde contre les sorts : Bonus de 2
– Empêche le lancement des sorts

Spécial (Limier):
– Onde de choc et Incinération n'infligent des dégâts qu'aux ennemis

Poids : 1

---

</details>

#### Infos sans spoiler :

- BGEE : La chaîne du prisonnier, l'anneau de calamité et l'anneau de pierre peuvent être obtenus (les autres objets sont quand même installés).
- SoD : le Livre de chants, "le souffle de l'Éther" et l'Anneau de Golem peuvent être obtenus.
- BG2EE : Tous les objets pouvant être obtenus dans SoA. Si vous commencez une nouvelle partie dans ToB, le sac de départ contiendra 1 ou 2 objets.
- IWDEE : L'anneau du Golem se trouve dans l'extension Trial of the Lurmaster. Le reste se trouve dans la campagne principale de IWD.


Les Runes de Caryll
-

#### Informations :

- Ce sont des objets ayant des effets sur l'ensemble du groupe.
- Elles peuvent être utilisés à volonté et fonctionnent mieux du point de vue du gameplay si le joueur peut passer librement de l'une à l'autre.
- Les personnages n'ont pas besoin de se trouver dans la même zone pour en bénéficier.
- Une seule rune peut être utilisée à la fois. Lorsqu'une rune est activée, elle supprime d'abord les effets octroyés par la précédente.

Remarque : les icônes sont légèrement différentes pour chaque rune. Elles n'ont pas un aspect extraordinaire, mais permettent de les différencier. L'image de la description est la même pour toutes les runes. Je n'ai pas réussi à dessiner quelque chose qui me plaisait, alors j'ai simplement utilisé l'un des BAM existant dans BG2.


#### Runes de Caryll :

- Griffure
- Prélèvement
- Distorsion
- Corruption
- Anomalie inversée
- Anomalie
- Sérénité
- Ardeur
- La Bête
- Acuité
- Pleine Lune
- Sève

<details>
  <summary>Descriptions</summary>

---

**Griffure**

Une des nombreuses runes attribuées à Caryll, un orfèvre qui aurait entendu et gravé les murmures des Grands Anciens avec d'étranges symboles. Cet objet applique ses effets à tous les membres du groupe.

Une seule rune peut être utilisée à la fois. Lorsqu'une rune est activée, elle supprime d'abord les effets octroyés par la précédente.

PARAMÈTRES :

Capacités de charge :
- Griffure (peut être utilisé à volonté)
- Zone d'effet : Le groupe
- Durée : 24 heures

5% de chances d'effectuer un coup critique et de provoquer une hémorragie, qui inflige 1 point de dégâts par round pendant un tour (pas de jet de sauvegarde possible) ; une même cible peut être blessée une fois par round et les effets sont cumulatifs.

Poids : 0

---

**Prélèvement**

Une des nombreuses runes attribuées à Caryll, un orfèvre qui aurait entendu et gravé les murmures des Grands Anciens avec d'étranges symboles. Cet objet applique ses effets à tous les membres du groupe.

Une seule rune peut être utilisée à la fois. Lorsqu'une rune est activée, elle supprime d'abord les effets octroyés par la précédente.

PARAMÈTRES :

Capacités de charge :
- Prélèvement (peut être utilisé à volonté)
- Zone d'effet : Le groupe
- Durée : 24 heures
  
Les coups critiques restaurent 9 points de vie.

Poids : 0

---

**Distorsion**

Une des nombreuses runes attribuées à Caryll, un orfèvre qui aurait entendu et gravé les murmures des Grands Anciens avec d'étranges symboles. Cet objet applique ses effets à tous les membres du groupe.

Une seule rune peut être utilisée à la fois. Lorsqu'une rune est activée, elle supprime d'abord les effets octroyés par la précédente.

PARAMÈTRES :

Capacités de charge :
- Distorsion (utilisable à volonté)
- Zone d'effet : Le groupe
- Durée : 24 heures

Les coups critiques restaurent 1 sort mémorisé.

Poids : 0

---

**Corruption**

Une des nombreuses runes attribuées à Caryll, un orfèvre qui aurait entendu et gravé les murmures des Grands Anciens avec d'étranges symboles. Cet objet applique ses effets à tous les membres du groupe.

Une seule rune peut être utilisée à la fois. Lorsqu'une rune est activée, elle supprime d'abord les effets octroyés par la précédente.

PARAMÈTRES :

Capacités de charge :
- Corruption (peut être utilisé à volonté)
- Zone d'effet : Le groupe
- Durée : 24 heures

Régénère 4 points de vie par round aux membres du groupe ayant moins de 50 % de leurs santés, 6 points de vie par round à moins de 25 %, et enfin 8 points de vie par round en dessous de 10 %.

Poids : 0

---

**Anomalie inversée**

Une des nombreuses runes attribuées à Caryll, un orfèvre qui aurait entendu et gravé les murmures des Grands Anciens avec d'étranges symboles. Cet objet applique ses effets à tous les membres du groupe.

Une seule rune peut être utilisée à la fois. Lorsqu'une rune est activée, elle supprime d'abord les effets octroyés par la précédente.

PARAMÈTRES :

Capacités de charge :
- Anomalie inversée (utilisable à volonté)
- Zone d'effet : Le groupe
- Durée : 24 heures

Vitesse de déplacement augmentée de 2 ; 1/2 attaque supplémentaire par round ; pénalité de 10 % au maximum de points de vie.

Poids : 0

---

**Anomalie**

Une des nombreuses runes attribuées à Caryll, un orfèvre qui aurait entendu et gravé les murmures des Grands Anciens avec d'étranges symboles. Cet objet applique ses effets à tous les membres du groupe.

Une seule rune peut être utilisée à la fois. Lorsqu'une rune est activée, elle supprime d'abord les effets octroyés par la précédente.

PARAMÈTRES :

Capacités de charge :
- Anomalie (peut être utilisé à volonté)
- Zone d'effet : Le groupe
- Durée : 24 heures

Bonus de 20 % au maximum de points de vie.

Poids : 0

---

**Sérénité**

Une des nombreuses runes attribuées à Caryll, un orfèvre qui aurait entendu et gravé les murmures des Grands Anciens avec d'étranges symboles. Cet objet applique ses effets à tous les membres du groupe.

Une seule rune peut être utilisée à la fois. Lorsqu'une rune est activée, elle supprime d'abord les effets octroyés par la précédente.

PARAMÈTRES :

Capacités de charge :
- Sérénité (peut être utilisé à volonté)
- Zone d'effet : Le groupe
- Durée : 24 heures

Bonus de 10 % de résistance à tous les dégâts physiques.

Poids : 0

---

**Ardeur**

Une des nombreuses runes attribuées à Caryll, un orfèvre qui aurait entendu et gravé les murmures des Grands Anciens avec d'étranges symboles. Cet objet applique ses effets à tous les membres du groupe.

Une seule rune peut être utilisée à la fois. Lorsqu'une rune est activée, elle supprime d'abord les effets octroyés par la précédente.

PARAMÈTRES :

Capacités de charge :
- Ardeur (peut être utilisé à volonté)
- Zone d'effet : Le groupe
- Durée : 24 heures

80 % de résistance au feu.

Poids : 0

---

**La Bête**

Une des nombreuses runes attribuées à Caryll, un orfèvre qui aurait entendu et gravé les murmures des Grands Anciens avec d'étranges symboles. Cet objet applique ses effets à tous les membres du groupe.

Une seule rune peut être utilisée à la fois. Lorsqu'une rune est activée, elle supprime d'abord les effets octroyés par la précédente.

PARAMÈTRES :

Capacités de charge :
- La Bête (peut être utilisé à volonté)
- Zone d'effet : Le groupe
- Durée : 24 heures

Transformation en loup-garou pendant les combats ; la métamorphose est instantanée, le personnage reprendra sa forme naturelle si aucun ennemi ne se trouve à portée de vue.

- Spécial : Les clercs et les paladins se transforment en loup-garou majeur.

Poids : 0

---

**Acuité**

Une des nombreuses runes attribuées à Caryll, un orfèvre qui aurait entendu et gravé les murmures des Grands Anciens avec d'étranges symboles. Cet objet applique ses effets à tous les membres du groupe.

Une seule rune peut être utilisée à la fois. Lorsqu'une rune est activée, elle supprime d'abord les effets octroyés par la précédente.

PARAMÈTRES :

Capacités de charge :
– Acuité (peut être utilisé à volonté)
  Zone d'effet : Le groupe
  Durée : 24 heures
Bonus de 1 aux jets d'attaque.

Poids : 0

---

**Pleine Lune**

Une des nombreuses runes attribuées à Caryll, un orfèvre qui aurait entendu et gravé les murmures des Grands Anciens avec d'étranges symboles. Cet objet applique ses effets à tous les membres du groupe.

Une seule rune peut être utilisée à la fois. Lorsqu'une rune est activée, elle supprime d'abord les effets octroyés par la précédente.

PARAMÈTRES :

Capacités de charge :
– Pleine Lune (peut être utilisé à volonté)
  Zone d'effet : Le groupe
  Durée : 24 heures
35 points d'expérience supplémentaires pour chaque ennemi vaincu par le groupe.

Poids : 0

---

**Sève**

Une des nombreuses runes attribuées à Caryll, un orfèvre qui aurait entendu et gravé les murmures des Grands Anciens avec d'étranges symboles. Cet objet applique ses effets à tous les membres du groupe.

Une seule rune peut être utilisée à la fois. Lorsqu'une rune est activée, elle supprime d'abord les effets octroyés par la précédente.

PARAMÈTRES :

Capacités de charge :
- Sève (peut être utilisé à volonté)
  Zone d'effet : Le groupe
  Durée : 24 heures
Transformation en flagelleur mental en cours de combats ; en contrepartie la sagesse et la constitution sont réduites à 5 pendant la métamorphose, le personnage reprendra sa forme naturelle si aucun ennemi ne se trouve à portée de vue.

Poids : 0

---

</details>

#### Notes de jeu :

- BG1 / SoD : Vous pouvez obtenir 5 runes au total (2 dans SoD).
- BG2 : Toutes les Runes peuvent être obtenus dans la partie SoA. Elles sont ajoutées dans l'inventaire au début de ToB, pour certains kits.
- IWDEE / HoW : Elles sont réparties dans divers donjons et autres lieux.
