# BWS-FR Fixpack

BWS-FR Fixpack est une compilation de correctifs, à la base destinés au BWS-FR, mais qui peut aussi être utilisé indépendamment.
Il suffit de l'exécuter après avoir décompressé vos mods dans le dossier du jeu, et avant de débuter vos installations de mod.   

Un second composant, à exécuter à la toute fin de votre installation, va vérifier divers problèmes connus, et vous suggèrera des corrections si possible

### Corrections

#### Corrections de bugs

- Alsaahir kit for BG2 v5.0
  - Mise à jour du fichier fl#add_kit_ee.tpa v1.1.4 => v1.1.5
  
- Artaport v2.0
  - SOD n'était pas correctement détecté

- Ascension v2.0.24
  - Déplacement des flèches de Gromnir des objets rapides vers le carquois (merci [@supasillyass](https://github.com/supasillyass) : https://github.com/InfinityMods/Ascension/pull/15)

- BG1 Unfinished Business v16.4
  - Correction d'une typo (merci [@Ychap](https://github.com/Ychap) : https://github.com/Pocket-Plane-Group/bg1ub/pull/3)

- Bridge's Block v1.6
  - Correction d'une typo lors de la vérification de la présence de Keldorn dans le groupe

- Chaos Sorcerer Kit v2.7
  - Mise à jour du fichier fl#add_kit_ee.tpa v1.1.3 => v1.1.5

- Check the Bodies v3.0
  - Mise à jour du fichier fl#add_kit_ee.tpa v1.1.2 => v1.1.5
  - Correction de la référence au kit Barbare dans divers scripts

- Derat's Unused Kits Pack v18
  - Correction pour les variables PxSORCELIERD et PxSORCELIERB qui ne sont pas initialisées avant la compilation des scripts

- Ding0's Quest Pack v3.5
  - Mise à jour de la librairie Detectable Spells v3-20180512 => v4.0.1

- Divine Remix v8.1 (TotoR115)
  - Le composant @600 ne pouvait pas s'installer sur une version EE sans le composant @109.
  - Mise à jour du fichier fl#add_kit_ee.tpa v1.1.4 => v1.1.5

- Endless BG1 v18.1
  - Correction d'une variable dans un script : HARTEEL_JOINED => SHARTEEL_JOINED

- Expanded Thief Stronghold v3.0.0
  - Correction de la référence d'une créature dans certaines conditions. (merci [@TotoR115](https://github.com/TotoR115) : https://github.com/SpellholdStudios/Expanded_Thief_Stronghold/issues/2)

- Gavin NPC v14
  - Correction de la vérification d'une variable (merci [@AngelGryph](https://github.com/AngelGryph) : https://github.com/Gibberlings3/Gavin_BG/commit/a85c8c8fd9d67eb46fc81faa6dfd86098013747b)

- Hanna NPC v2.5
  - Le code de gestion de la transition du PNJ était inclu dans le composant 6 au lieu du composant 0.
  - L'identifiant IC_LICH était toujours ajouté, même s'il existait déjà.
  - Correction de références à Keldorn et Yoshimo dans un dialogue : Keldor => Keldorn, Yhosimo => Yoshimo

- Item Revision v4beta10sd19
  - Dans certains cas, si une armure possédait déjà de la résistance à un dégât physique, cette dernière était augmentée du double que prévu.
    Ex: DWCHAN02, DWPLAT01, ISHCHA

- L'interplan, un magasin dedie à la magie v7
  - Correction du parchemin "Porte vers Linterplan" (merci [@deratiseur](https://www.baldursgateworld.fr/memberlist.php?mode=viewprofile&u=8352) : https://www.baldursgateworld.fr/viewtopic.php?f=749&p=509113#p509113)
 
- Made in heaven: Encounters & Quests
  - Correction du remplacement des références de bdwightj dans le script bdjunia.dlg

- Monk Overhaul v1.3
  - SOD n'était pas correctement détecté
  
- Refinements v4.36
  - Mise à jour du fichier fl#add_kit_ee.tpa v1.1.2 => v1.1.5
  - zpwi606.spl: L'opcode 31 des niveaux 19 et 20 augmentaient la résistance de 100% au lieu d'écraser la valeur comme le fait les niveaux inférieurs.
  - Correction de l'installation du composant "Angelame : Nouveau kit de guerrier"

- Rodeur de l'ombre v1.2
  - Mise à jour du fichier fl#add_kit_ee.tpa v1.0.5 => v1.1.5

- Rogue Rebalancing v4.92
  - Mise à jour de la librairie Detectable Spells v3-20180512 => v4.0.1

- Secret of Bone Hill (EET) v34
  - Correction d'une référence dans un dialogue : Mincs => Minsc

- Sheena, a Half Dragon Tale NPC v2.6
  - Correction de la vérification de la présence de HaveSpellRES(S:RES*) dans le fichier Trigger.ids
  - Correction d'une référence dans un script : "Myself" => Myself
  - Correction d'une référence dans un dialogue : Sheena => K#Sheena

- Song and Silence v16
  - Mise à jour du fichier fl#add_kit_ee.tpa v1.1.3 => v1.1.5

- Southern Edge v4.2
  - Correction de références à un objet dans un dialogue : BOOK9C => MISC9C

- Spiritwalker - A Shaman Shapeshifter Kit v1.4
  - Mise à jour du fichier fl#add_kit_ee.tpa v1.1.2 => v1.1.5

- Stratagems v34.3
  - Erreur de syntaxe qui empêche le script /priest/spellchoices_defensive/demivrgvs/druid.tph de s'exécuter.
  - Correction d'un problème où les items rndtre01 et rndtre02 étaient remplacés par null.
  - Correction d'un problème où un item WIZARD_S.itm était ajouté dans certains magasins.
  - Correction du prix demandé par Gaelan Bayle qui n'était pas mis à jour dans les textes à cause de l'espace insécable non géré.
  - Correction de divers appels à la fonction RandomNum() (merci [@supasillyass](https://github.com/supasillyass) et [@Ychap](https://github.com/Ychap) : https://github.com/Gibberlings3/SwordCoastStratagems/pull/44)
  - Correction du lancement du sort "BURNING_MAN_KEENING" qui était lancé en boucle (merci [@mleduque](https://github.com/mleduque))
  - Correction de typo avec les capacités de haut niveau innées (merci [@Ychap](https://github.com/Ychap) : https://github.com/Gibberlings3/SwordCoastStratagems/pull/48)
  - Correction d'un texte erroné de Château-Suif dans EET (merci [@Ychap](https://github.com/Ychap) : https://github.com/Gibberlings3/SwordCoastStratagems/pull/49)
  - Correction d'un texte erroné sur l'écran de TotSC dans EET (merci [@Ychap](https://github.com/Ychap) : https://github.com/Gibberlings3/SwordCoastStratagems/pull/50)
  - Correction du spawning de certains bandits (merci [@Ychap](https://github.com/Ychap) : https://github.com/Gibberlings3/SwordCoastStratagems/pull/51)
  - Correction de la suppression excessive de certains effets (merci [@Ychap](https://github.com/Ychap) : https://github.com/Gibberlings3/SwordCoastStratagems/pull/52)
  - Correction du groupement dans le journal, d'une étape de la quête "L'île mystérieuse" (merci [@Ychap](https://github.com/Ychap) : https://github.com/Gibberlings3/SwordCoastStratagems/pull/55)
  - Correction de la compétence utilisée par l'objet "dw#kob01" qui était "Epée longue" au lieu de "Dague"
  - Correction du composant NPC customisation pour EET (merci [@DavidW](https://www.gibberlings3.net/profile/1067-davidw/) : https://www.gibberlings3.net/forums/topic/36487-npc-customization/#comment-326619)

- The Beaurin Legacy v5.3
  - Correction de références à Haer'Dalis dans un dialogue : Haer'Dalis => HaerDalis
  - Correction d'un OR nécessitant 10 triggers alors qu'il n'y en a que 9

- The Stone of Askavar v2.2
  - SOAITM27.itm
    - Correction du parameter2 de l'opcode 115 : 4 => 0
  - SOAITM30.itm
    - Correction du type de compétence : "Épée longue" => "Épée à deux mains"
    - Correction du parameter2 de l'opcode 115 : 4 => 0

- Themed Tweaks v0.4
  - Correction de la référence d'une custscene : #LCWBQ030 => #LCWBQ03

- Tweaks Anthology v15
  - Correction d'un problème de typo dans le composant "Personnaliser le nom des sauvegardes automatiques" (merci [@Argent77](https://github.com/Argent77) : https://github.com/Gibberlings3/Tweaks-Anthology/pull/61)
  - Mise à jour du fichier fl#add_kit_ee.tpa v1.0.5 => v1.1.5

- Wheels of Prophecy v8.5
  - Corrections (merci [@abalabokhin](https://github.com/abalabokhin) : https://github.com/abalabokhin/WheelsOfProphecy/commit/4266f3f5e6e6b11f7f16d5f2bcd4dca17c3f382d et https://github.com/abalabokhin/WheelsOfProphecy/commit/701bb3b91ace1582939e4704a0a3b4921c68790d)

#### Corrections de compatibilité

- Ascension v2.0.24
  - Compatibilité avec EE Fixpack

- aTweaks v4.53
  - Compatibilité avec EE Fixpack qui supprime des entrées dans le fichier object.ids

- BG1 Unfinished Business v16.4
  - Compatibilité avec EET : Correction d'un dialogue avecv Arkion (merci [@GraionDilach](https://github.com/GraionDilach) : https://github.com/Pocket-Plane-Group/bg1ub/pull/2)

- Check the Bodies v3.0
  - Compatibilité avec EET pour que les zones s'ajoutent dans le menu de triche.
  - Compatibilité avec EET en déplaçant la zone du Cercle Druidique pour qu'il ne chevauche plus la zone de Bois Manteau (merci [@GraionDilach](https://github.com/GraionDilach) : https://github.com/SpellholdStudios/Check_the_Bodies/pull/17)

- Gerri's BGT NPC Portraits v3.1
  - Le composant "Portraits for BG1 Romantic Encounters" se basait sur le composant 0 de "BG1 Romantics Encounters" qui n'existe plus et est remplacé par les composants 100 à 105.

- Item Revision v4beta10sd19
  - Le mod vérifie si le composant "Services etendus des temples" de Atweaks est installé, mais le numéro du composant est incorrect (600 au lieu de 510).

- Olvyn Tweaks
  - La description des compétences d'arme n'était pas modifiée sous EET

- RelieveWizardSlayer.tp2 v1.7
  - Compatibilité avec "Wizard Slayer Rebalancing", le tp2 et le numéro du composant étaient incorrects

- Rogue Rebalancing v4.92
  - La description du Maître-lames, couplée au composant "4250 - Changer les sequenceurs de sorts et les contingences en capacites speciales" de Stratagems, générait une description de plus de 4096 caractères, ce qui faisait crasher le jeu lorsque l'on tentait de sélectionner ce kit.
    La description de la capacité "Démonstration Martiale" a été diminuée.
  - Compatibilité avec Iwdification (merci [@CamDawg](https://github.com/CamDawg) : https://github.com/FredrikLindgren/rr/pull/11)

- Sheena, a Half Dragon Tale NPC v2.6
  - Remplacement des RemoveSpellRES(S:RES*,O:Target) par ActionOverride(O:Actor*,RemoveSpellRES(S:RES*))
    La nouvelle signature de RemoveSpellRES() provoque des erreurs pour les mods installés après

- Stratagems v34.3
  - Compatibilité avec EET, en corrigeant la vérification des chapitres dans divers scripts ssl.

- Thalantyr Item Upgrade v4.2.5
  - Compatibilté avec EET, en prenant en compte l'objet BOOT02ZH (merc [@BardezAnAvatar](https://github.com/BardezAnAvatar) : https://github.com/CrevsDaak/thalan/pull/11)

- Tweaks Anthology v15
  - Compatibilité avec Edwin Romance afin de pouvoir sélectionner le portrait d'Edwina
  - Compatibilité avec EET : Correction du script de la zone de Château-Suif (merci [@Ychap](https://github.com/Ychap) : https://github.com/Gibberlings3/Tweaks-Anthology/pull/55)
  - Compatibilité avec EET : Suppression d'options de réponse en double (merci [@CamDawg](https://github.com/CamDawg) : https://github.com/Gibberlings3/Tweaks-Anthology/commit/deebc0a7d8a9563cd8f20bf3a7f135aa3fc42301)

#### Traductions et corrections d'orthographe

- 5E-style spellcasting v2.5.1
  - Traductions des quelques lignes manquantes
  - Correction de l'altération des descriptions de certains kits de barde ajoutés par Might & Guile 

- Baldur's Gate Romantic Encounters v11.0
  - Ajout de traductions manquantes (merci [Le Marquis d'Oghmatique](https://www.baldursgateworld.fr/memberlist.php?mode=viewprofile&u=8761) : https://www.baldursgateworld.fr/viewtopic.php?p=508666#p508666)

- BG1 NPC Project v30
  - Correction d'une typo (merci [@Krabator](https://www.baldursgateworld.fr/memberlist.php?mode=viewprofile&u=9392))

- Check the Bodies v3.0
  - Correction de l'encodage du fichier wsetup.tra

- EET (Enhanced Edition Trilogy) Tweaks v1.12
  - Ajout de la traduction

- Enhanced Powergaming Scripts v12.5
  - Ajout de la traduction (merci [@JohnBob](https://github.com/11jo))

- Made in heaven: Encounters & Quests
  - Correction de la tournure anglaise lors du renommage de certains sortilèges

- Magic Store of Vergadain v3.0
  - Mise à jour de la traduction (merci [@JohnBob](https://github.com/11jo) : https://github.com/Argent77/A7-MagicStore/commit/139d94c2d0ba1f6858f3afb28aef13e3c6531a31)

- Olvyn Tweaks
  - Corrections de caractères majuscules accentués qui fonctionnent sans problème avec EE

- RelieveWizardSlayer.tp2 v1.7
  - Mini traduction pour la partie qui remplace la description du kit du tueur de magiciens de "Wizard Slayer Rebalancing"

- Sheena, a Half Dragon Tale NPC v2.6
  - Correction de l'encodage des fichiers de traduction

- Skills-and-Abilities v2.3
  - Ajout de la traduction (merci [@JohnBob](https://github.com/11jo))

- Stratagems v34.3
  - Mise à jour de la traduction du fichier difficulty.tra (merci [@Krabator](https://github.com/Krabator) : https://github.com/Gibberlings3/SwordCoastStratagems/pull/47)
  - Mise à jour de la traduction des sorts (merci [@Jazira33](https://github.com/Jazira33) : https://github.com/Gibberlings3/SwordCoastStratagems/pull/43)

- SubtleD's Item Tweaks v1.3.1
  - Ajout de la traduction (merci [@mleduque](https://github.com/mleduque) : https://github.com/subtledoctor/SubtleD_Item_Tweaks/pull/1)

- SubtleD's Spell Tweaks v2.6
  - Mise à jour de la traduction (merci [@mleduque](https://github.com/mleduque) : https://github.com/subtledoctor/SubtleD_Spell_Tweaks/pull/15)

- SubtleD's Stat Overhauls v1.3
  - Ajout de la traduction (merci [@mleduque](https://github.com/mleduque) : https://github.com/subtledoctor/SubtleD_Stat_Overhauls/pull/1)

- Tactics-Remix v0.6.2-beta
  - Mise à jour de la traduction (merci [@JohnBob](https://github.com/11jo))

- Thalantyr Item Upgrade v4.2.5
  - Corrections de la traduction

- The Enhanced Edition Fixpack vBeta 1
  - Ajout de la traduction

- Unique Artifacts v7.13
  - Ajout de la traduction

- Wheels of Prophecy v8.5
  - Trafication de 2 chaînes manquantes (merci [@abalabokhin](https://github.com/abalabokhin) : https://github.com/abalabokhin/WheelsOfProphecy/commit/78e395efe26eea6c3e94ea3c49da26970a8cf222)

#### Patchs repris et adaptés du BiG World Fixpack

- Animal Companions v1.6
- Homeward bound v8
- Lolfixer v19022016
- The Grey Clan Episode I: In Candlelight v1.9

### Vérifications

- Le fichier **splstate.ids**
  Vérifie si des identifiants supérieurs à 255 existent. Ces identifiants ne sont pas pris en compte par le moteur du jeu par certaines fonctions de script (Ex: CheckSpellState()) et cela peut provoquer divers bugs.
