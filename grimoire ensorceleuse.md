

# Grimoire

## Niveau 0 / Tour de magie

- *Aspersion acide*: Boule d'acide visant une ou deux cibles proches pour 1d6 dégâts.
- *Aura du héros*: Le PJ obtient un <em>avantage</em> aux tests de Charisme.
- *Contact glacial*: Une main spectrale attaque une cible et lui inflige 1d8 dégâts nécrotiques.
- *Illusion mineure*: Créer un son ou une image représentant un objet.
- *Lumière*: L'objet ciblé émet de la lumière dans un rayon de 12 mètres.
- *Lumières dansantes*: Crée des torches ou des lumières flottants dans l'air.
- *Main du mage*: Fait apparaître et permet de contrôler une main spectrale.
- *Message*: Conversation murmurée à distance.
- *Poigne électrique*: Attaque de contact infligeant 1d8 dégâts de foudre.
- *Porte-bonheur*: Résistance aux dégâts élémentaires.
- *Prestidigitation*: Tours de magie basiques.
- *Rayon de givre*: Rayon infligeant 1d8 dégâts de froid et qui ralentit la cible.
- *Réparation*: Permet de réparer un objet cassé ou déchiré.
- *Trait de feu*: Trait enflammé qui inflige 1d10 dégâts et embrase les objets inflammables.
- *Viser juste*: Le PJ obtient un <em>avantage</em> sur son prochain jet d'attaque.




### Aspersion acide
```yml
title: "Aspersion acide"
description: "Boule d'acide visant une ou deux cibles proches pour 1d6 dégâts."
school: "Invocation"
level: 0
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous lancez une boule d'acide. Choisissez une créature à portée, ou deux créatures à portée situées à 1,50 mètre ou moins l'une de l'autre. Une cible doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité, sinon elle subit 1d6 dégâts d'acide.

Les dégâts du sort augmentent de 1d6 quand vous atteignez le niveau 5 (2d6), 11 (3d6) et 17 (4d6).


### Aura du héros
```yml
title: "Aura du héros"
description: "Le PJ obtient un <em>avantage</em> aux tests de Charisme."
school: "Enchantement"
level: 0
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "personnelle"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Une aura captivante émane de vous dans un rayon de 1,50 mètre. Vous bénéficiez d'un [_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) à tous vos tests de Charisme visant les créatures situées dans l'aura. À la fin du sort, les créatures qui en ont subi l'influence peuvent faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) d'Intelligence. En cas de réussite, elles se rendent compte avoir été influencées par magie et elles peuvent, à la discrétion du MJ, en concevoir de l'hostilité.

Le rayon d'action de ce sort double lorsque vous atteignez le niveau 5 (3 mètres), puis le niveau 11 (6 mètres) et enfin au niveau 17 (12 mètres).


### Contact glacial
```yml
title: "Contact glacial"
description: "Une main spectrale attaque une cible et lui inflige 1d8 dégâts nécrotiques."
school: "Nécromancie"
level: 0
concentration: false
casting_time: "1 action"
duration: "1 round"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous faites apparaître une main fantomatique et squelettique sur l'emplacement d'une créature située à portée. Faites un [jet d'attaque](/combattre/#jets-d-attaque) de sort à distance contre la créature pour la transir de froid. Si l'attaque touche, la victime reçoit 1d8 dégâts nécrotiques et ne peut pas récupérer de point de vie avant le début de votre prochain tour. Jusque-là, la main s'accroche à elle.

Si votre cible est un mort-vivant, il subit en plus un [_désavantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors des jets d'attaque effectués contre vous jusqu'à la fin de votre prochain tour.

Les dégâts du sort augmentent de 1d8 quand vous atteignez les niveaux 5 (2d8), 11 (3d8) et 17 (4d8).


### Illusion mineure
```yml
title: "Illusion mineure"
description: "Créer un son ou une image représentant un objet."
school: "Illusion"
level: 0
concentration: false
casting_time: "1 action"
duration: "1 minute"
range: "9 mètres"
components:
  verbal: false
  somatic: true
  material: true
  materials: "un morceau de toison"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Vous créez à portée un son ou une image représentant un objet. L'illusion persiste pendant toute la durée du sort, et se dissipe si vous révoquez le sort par une action ou si vous lancez de nouveau ce sort.

Si vous créez un son, son volume peut aller du simple murmure au hurlement. Ce peut être votre voix, celle de quelqu'un d'autre, le rugissement d'un lion, un battement de tambours ou tout autre son de votre choix. Ce bruit persiste sans faiblir pendant toute la durée du sort, à moins que vous ne préfériez émettre des sons distincts à différents moments pendant la durée du sort.

Si vous créez une image (comme une chaise, des empreintes boueuses ou un petit coffre), elle doit tenir dans un cube de 1,50 mètre d'arête. L'image ne s'accompagne pas de son, de lumière, d'odeur, ni d'autre effet sensoriel. Une interaction physique avec l'image révèle immédiatement qu'elle n'est qu'une illusion, car les objets la traversent.

Si une créature utilise son action pour examiner le son ou l'image, elle comprend qu'il s'agit d'une illusion si elle réussit un test d'Intelligence (Investigation) opposé au DD du [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de votre sort. Si une créature perce l'illusion à jour, celle-ci perd toute substance pour elle.


### Lumière
```yml
title: "Lumière"
description: "L'objet ciblé émet de la lumière dans un rayon de 12 mètres."
school: "Évocation"
level: 0
concentration: false
casting_time: "1 action"
duration: "1 heure"
range: "contact"
components:
  verbal: true
  somatic: false
  material: true
  materials: "une luciole ou de la mousse phosphorescente"
ritual: false
classes:
    - Barde
    - Clerc
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
```
Vous touchez un objet qui ne fait pas plus de 3 mètres dans chaque dimension. Jusqu'à la fin du sort, il émet une vive lumière dans un rayon de 6 mètres et une faible lumière dans un rayon additionnel de 6 mètres. Vous pouvez colorer cette lumière comme vous le souhaitez. Il suffit de recouvrir complètement l'objet avec quelque chose d'opaque pour bloquer la lumière. Le sort se termine si vous le lancez de nouveau ou si vous le révoquez en dépensant une action.

Si vous visez un objet porté ou transporté par une créature hostile, cette dernière doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité pour éviter les effets du sort.


### Lumières dansantes
```yml
title: "Lumières dansantes"
description: "Crée des torches ou des lumières flottants dans l'air."
school: "Évocation"
level: 0
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un bout de phosphore ou d'orme, ou un ver luisant"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
```
Vous créez jusqu'à quatre lumières de la taille d'une torche qui apparaissent à portée. Elles ressemblent à des lanternes, des torches ou des orbes luisants qui flottent dans les airs pendant toute la durée du sort. Vous pouvez aussi les combiner pour obtenir une forme brillante vaguement humanoïde de taille M. Quelle que soit l'option choisie, chaque source lumineuse offre une lumière faible dans un rayon de 3 mètres.

À votre tour et par une action bonus, vous pouvez déplacer les lumières sur un maximum de 18 mètres pour les installer ailleurs, mais toujours à portée. Une lumière créée via ce sort doit toujours se trouver à 6 mètres ou moins d'une autre émanant du même sort. Elle s'éteint si elle passe hors de portée.


### Main du mage
```yml
title: "Main du mage"
description: "Fait apparaître et permet de contrôler une main spectrale."
school: "Invocation"
level: 0
concentration: false
casting_time: "1 action"
duration: "1 minute"
range: "9 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Une main spectrale flottante apparaît à portée, en un point de votre choix. Elle persiste pendant toute la durée du sort ou jusqu'à ce que vous révoquiez le sort par une action. La main disparaît si elle s'éloigne à plus de 9 mètres de vous ou si vous relancez le sort.

Vous pouvez utiliser votre action pour contrôler la main et vous en servir pour manipuler un objet, ouvrir une porte ou un récipient qui ne sont pas verrouillés, placer un objet dans un récipient ouvert ou l'en sortir, ou bien verser le contenu d'une flasque. Vous pouvez déplacer la main d'un maximum de 9 mètres à chaque fois que vous l'utilisez.

La main ne peut pas attaquer, activer un objet magique, ni transporter plus de 5 kilogrammes.


### Message
```yml
title: "Message"
description: "Conversation murmurée à distance."
school: "Transmutation"
level: 0
concentration: false
casting_time: "1 action"
duration: "1 round"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un petit bout de fil de cuivre"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
```
Vous pointez du doigt une créature à portée et murmurez un message. La cible (et elle seule) l'entend et peut répondre dans un murmure que vous êtes le seul à entendre.

Vous pouvez lancer ce sort au travers d'un objet solide si vous connaissez bien la cible et savez qu'elle se trouve de l'autre côté de cet obstacle. Le sort est bloqué par un silence magique, 30 centimètres de pierre, 2,5 centimètres de métal ordinaire, une mince couche de plomb ou 90 centimètres de bois. Le sort n'a pas besoin de voyager en ligne directe, il peut contourner les angles et franchir les ouvertures.



### Poigne électrique
```yml
title: "Poigne électrique"
description: "Attaque de contact infligeant 1d8 dégâts de foudre."
school: "Évocation"
level: 0
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "contact"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
La foudre jaillit de votre main et bondit sur la créature que vous tentez de toucher. Faites une attaque de sort au corps-à-corps contre la cible. Vous bénéficiez d'un [_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors du [jet d'attaque](/combattre/#jets-d-attaque) si votre cible porte une armure métallique. Si vous touchez la cible, elle subit 1d8 dégâts de foudre et ne peut pas effectuer de réaction avant le début de son prochain tour.

Les dégâts du sort augmentent de 1d8 quand vous atteignez le niveau 5 (2d8), 11 (3d8) et 17 (4d8).


### Porte-bonheur
```yml
title: "Porte-bonheur"
description: "Résistance aux dégâts élémentaires."
school: "Abjuration"
level: 0
concentration: false
casting_time: "1 action"
duration: "1 round"
range: "personnel"
components:
  verbal: true
  somatic: true
  material: true
  materials: "objet porte-bonheur"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous agrippez votre objet porte-bonheur (gri-gri, talisman, amulette, etc.) et, jusqu'à la fin de votre prochain tour, vous bénéficiez d'une résistance aux dégâts élémentaires (acide, feu, froid, foudre).


### Prestidigitation
```yml
title: "Prestidigitation"
description: "Tours de magie basiques."
school: "Transmutation"
level: 0
concentration: false
casting_time: "1 action"
duration: "jusqu'à 1 heure"
range: "3 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Ce sort est un tour de magie basique que les novices utilisent pour s'entraîner. Vous l'utilisez pour créer à portée l'un des effets magiques suivants :
* Vous créez un effet sensoriel immédiat et inoffensif, comme une pluie d'étincelles, un coup de vent, de faibles notes de musique ou une odeur étrange.
* Vous allumez ou éteignez instantanément une chandelle, une torche ou un petit feu de camp.
* Vous nettoyez ou salissez instantanément un objet ne faisant pas plus de 30 décimètres cubes.
* Vous refroidissez, réchauffez ou aromatisez jusqu'à 30 décimètres cubes de matière non vivante pendant 1 heure.
* Vous faites apparaître une couleur, une petite marque ou un symbole sur un objet ou une surface pendant 1 heure.
* Vous créez un colifichet non magique ou une image illusoire tenant dans votre main, qui persiste jusqu'à la fin de votre prochain tour.

Si vous lancez le sort à plusieurs reprises, vous ne pouvez pas avoir plus de trois effets non instantanés actifs à la fois. Vous pouvez révoquer un tel effet par une action.


### Rayon de givre
```yml
title: "Rayon de givre"
description: "Rayon infligeant 1d8 dégâts de froid et qui ralentit la cible."
school: "Évocation"
level: 0
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Un rayon de lumière d'un blanc bleuté file vers une créature à portée. Faites une attaque de sort à distance contre la cible. Si vous la touchez, elle subit 1d8 dégâts de froid et sa vitesse est réduite de 3 mètres jusqu'au début de votre prochain tour.

Les dégâts du sort augmentent de 1d8 quand vous atteignez le niveau 5 (2d8),11 (3d8) et 17 (4d8).


### Réparation
```yml
title: "Réparation"
description: "Permet de réparer un objet cassé ou déchiré."
school: "Transmutation"
level: 0
concentration: false
casting_time: "1 minute"
duration: "instantanée"
range: "contact"
components:
  verbal: true
  somatic: true
  material: true
  materials: "deux magnétites"
ritual: false
classes:
    - Barde
    - Clerc
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
```
Ce sort répare un objet cassé ou déchiré en un seul point, comme un maillon de chaîne cassé, deux moitiés d'une clef brisée, une cape déchirée ou une outre de vin qui fuit. Pour cela, vous devez toucher l'objet et la cassure ou la déchirure ne doit pas mesurer plus de 30 centimètres dans chaque dimension. Le problème se répare et il n'en reste plus trace.

Le sort permet de réparer un objet magique ou une créature artificielle, mais pas de restaurer sa magie.

### Trait de feu
```yml
title: "Trait de feu"
description: "Trait enflammé qui inflige 1d10 dégâts et embrase les objets inflammables."
school: "Évocation"
level: 0
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous lancez un trait enflammé sur une créature ou un objet à portée. Faites une attaque de sort à distance contre la cible. Si vous touchez, elle subit 1d10 dégâts de feu. Si le sort touche un objet inflammable qui n'est ni porté ni transporté, il s'embrase.

Les dégâts du sort augmentent de 1d10 quand vous atteignez le niveau 5 (2d10), le niveau 11 (3d10) et le niveau 17 (4d10).


### Viser juste
```yml
title: "Viser juste"
description: "Le PJ obtient un <em>avantage</em> sur son prochain jet d'attaque."
school: "Divination"
level: 0
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 round"
range: "9 mètres"
components:
  verbal: false
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous tendez la main et pointez du doigt une cible à portée. Votre magie vous donne un bref aperçu de ses défenses. À votre prochain tour, vous avez l'[_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors de votre premier [jet d'attaque](/combattre/#jets-d-attaque) contre elle, à condition que le sort ne se soit pas terminé avant.




## Niveau 1

### Armure du mage
```yml
title: "Armure du mage"
description: "La CA de base de la cible devient 13 + modificateur de Dextérité."
school: "Abjuration"
level: 1
concentration: false
casting_time: "1 action"
duration: "8 heures"
range: "contact"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un bout de cuir tanné"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous touchez une créature consentante qui ne porte pas d'armure et l'enveloppez d'une force magique protectrice jusqu'à la fin du sort. La CA de base de la cible passe à 13 + son modificateur de Dextérité. Le sort se termine si la cible revêt une armure ou si vous révoquez le sort par une action.





### Bouclier
```yml
title: "Bouclier"
description: "Réaction, +5 à la CA et bloque les projectiles magiques."
school: "Abjuration"
level: 1
concentration: false
casting_time: "1 réaction à effectuer lorsque vous êtes touché par une attaque ou un sort de projectile magique"
duration: "1 round"
range: "personnelle"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Une barrière invisible faite de force magique apparaît autour de vous et vous protège. Jusqu'au début de votre prochain tour, vous obtenez un bonus de +5 à la CA, y compris contre l'attaque qui a déclenché l'incantation du sort, et vous ne subissez aucun dégât de la part du sort <ST s="projectile-magique" />.



### Charme-personne
```yml
title: "Charme-personne"
description: "La cible <em>charmée</em> se considère comme l'amie du PJ."
school: "Enchantement"
level: 1
concentration: false
casting_time: "1 action"
duration: "1 heure"
range: "9 mètres"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Barde
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Vous tentez de charmer un humanoïde se trouvant à portée et dans votre champ de vision. Il doit faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse, pour lequel il dispose d'un [_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) si vous ou vos compagnons êtes actuellement en train de le combattre. S'il rate son test, il est [_charmé_](/gerer-la-sante-du-personnage/#charme) par vous jusqu'à la fin du sort ou jusqu'à ce que vous ou vos compagnons lui fassiez du mal. La créature [_charmée_](/gerer-la-sante-du-personnage/#charme) vous considère comme un ami. Quand le sort se termine, elle sait que vous l'avez charmée.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, vous pouvez charmer une créature de plus par niveau au-delà du niveau 1. Toutes les cibles doivent se trouver à 9 mètres ou moins les unes des autres lorsque vous lancez le sort.



### Compréhension des langues
```yml
title: "Compréhension des langues"
description: "Le PJ comprend les langages écrits ou parlés."
school: "Divination"
level: 1
concentration: false
casting_time: "1 action"
duration: "1 heure"
range: "personnelle"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une pincée de suie et de sel"
ritual: true
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Pendant toute la durée du sort, vous comprenez le sens littéral de tout langage parlé que vous entendez. Vous comprenez aussi les langues écrites que vous voyez, à condition de toucher la surface sur laquelle les mots ont été tracés. Il vous faut 1 minute pour lire une page de texte.

Ce sort ne décode pas les messages secrets compris dans un texte ni les glyphes qui ne correspondent pas à un langage écrit, comme un symbole magique.



### Couleurs dansantes
```yml
title: "Couleurs dansantes"
description: "Cône de lumières colorées qui <em>aveuglent</em> les cibles."
school: "Illusion"
level: 1
concentration: false
casting_time: "1 action"
duration: "1 round"
range: "personnelle (cône de 4,50 mètres)"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une poignée de poudre ou de sable, colorée en rouge, jaune et bleu"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Un éventail de lumières colorées éblouissantes jaillit de votre main. Lancez 6d10. Le total représente le nombre de points de vie de créatures que le sort affecte. Les créatures situées dans un cône de 4,50 mètres, prenant votre personne comme point d'origine, sont affectées dans l'ordre croissant de leurs points de vie actuels (en ignorant les créatures <RT l="inconscientes" t="inconscient"/> et les créatures <RT l="aveuglées" t="aveugle"/>).

Chaque créature affectée, en commençant par celle qui possède actuellement le moins de points de vie, est <RT l="aveuglée" t="aveugle"/> jusqu'à la fin du sort. Soustrayez du total obtenu le nombre de points de vie actuel de chaque créature affectée avant de passer à la suivante, en choisissant chaque fois celle qui possède le moins de points de vie. Pour qu'une créature soit affectée, elle doit posséder un nombre de points de vie actuels inférieur ou égal au total restant.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, lancez 2d10 supplémentaires par niveau au-delà du niveau 1.


### Déguisement
```yml
title: "Déguisement"
description: "Modifie l'apparence du PJ."
school: "Illusion"
level: 1
concentration: false
casting_time: "1 action"
duration: "1 heure"
range: "personnelle"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
```
Vous faites en sorte que votre personne (y compris vos vêtements, votre armure, vos armes et les autres objets en votre possession) prenne une apparence différente jusqu'à la fin du sort ou jusqu'à ce que vous utilisiez une action pour y mettre un terme. Vous pouvez passer pour une personne de 30 centimètres de plus ou de moins, sembler gros, maigre ou entre les deux. Vous ne pouvez pas changer de morphologie, vous devez choisir une forme possédant la même conformation que vous au niveau des membres. En dehors de cela, les détails de l'illusion sont laissés à votre imagination.

Les changements qu'apporte le sort ne résistent pas à un examen physique. Par exemple, si vous l'utilisez pour ajouter un chapeau à votre tenue, les objets passent au travers et toute personne qui essaie de le toucher ne sentira que de l'air, ou des cheveux et un crâne. Si vous utilisez le sort pour paraître plus mince qu'en réalité, la main de quelqu'un qui tente de vous toucher se heurtera à vous alors que, visuellement, elle semble encore dans le vide.

Pour percer votre déguisement à jour, une créature peut dépenser une action pour vous examiner. Elle doit alors réussir un test d'Intelligence (Investigation) contre le DD du [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) du sort.





### Détection de la magie
```yml
title: "Détection de la magie"
description: "Le PJ perçoit la présence de magie dans un rayon de 9 mètres."
school: "Divination"
level: 1
concentration: true
casting_time: "1 action"
duration: "jusqu'à 10 minutes"
range: "personnelle"
components:
  verbal: true
  somatic: true
  material: false
ritual: true
classes:
    - Barde
    - Clerc
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Paladin
    - Rôdeur
```
Pendant toute la durée du sort, vous percevez la présence de magie dans un rayon de 9 mètres autour de vous. Si vous percevez ainsi la magie, vous pouvez utiliser votre action pour discerner une faible aura autour d'une créature ou d'un objet visible dans la zone et imprégné de magie. Vous découvrez aussi à quelle école appartient cette magie, le cas échéant.

Le sort ignore la plupart des obstacles, mais il ne peut pas franchir 30 centimètres de pierre, 2,5 centimètres de métal ordinaire, une mince feuille de plomb, ni 1 mètre de bois ou de terre.





### Geyser d'énergie
```yml
title: "Geyser d'énergie"
description: "De l'énergie jaillit du sol et inflige 3d8 dégâts du type d'énergie choisi."
school: "Évocation"
level: 1
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "27 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une petite poire remplie d'air"
ritual: false
classes:
    - Ensorceleur/Sorcelame
```
Un geyser d'énergie jaillit du sol d'un endroit que vous spécifiez dans la portée du sort. Vous choisissez acide, foudre, feu, froid, poison ou tonnerre comme type d'énergie pour le geyser. Chaque créature située dans le cylindre de 1,50 mètre de diamètre et de 6 mètres de haut doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité, sans quoi elle subit 3d8 dégâts du type préalablement déterminé. Si le jet est réussi, les dégâts sont réduits de moitié.

**À plus haut niveau**. Lorsque vous lancez ce sort en utilisant un emplacement de sort de niveau 2 ou supérieur, les dégâts sont augmentés de 1d8 par niveau au-delà du niveau 1.



### Image silencieuse
```yml
title: "Image silencieuse"
description: "Permet de créer une image illusoire silencieuse."
school: "Illusion"
level: 1
concentration: true
casting_time: "1 action"
duration: "jusqu'à 10 minutes"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un morceau de toison"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
```
Vous créez l'image d'un objet, d'une créature ou d'un phénomène visible tenant dans un cube de 4,50 mètres de côté. L'image apparaît en un point situé à portée et persiste pendant toute la durée du sort. L'image comporte seulement des composantes visuelles, elle ne s'accompagne pas d'odeur, de son, ni d'autre effet sensoriel.

Vous pouvez utiliser votre action pour déplacer l'image vers un autre point à portée. Pendant qu'elle se déplace, vous pouvez modifier son apparence pour donner l'impression d'un mouvement naturel. Par exemple, si vous créez l'image d'une créature et que vous la déplacez, vous pouvez modifier l'image pour donner l'impression que la créature est en train de marcher.

Les interactions physiques révèlent que l'image n'est qu'une illusion, car les objets la traversent. Si une créature utilise son action pour examiner l'image, elle comprend que c'est une illusion à condition de réussir un test d'Intelligence (Investigation) contre le DD du [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de votre sort. Si une créature perce l'illusion à jour, elle voit à travers l'image.



### Léger comme une plume
```yml
title: "Léger comme une plume"
description: "Ralentit la chute de 5 cibles."
school: "Transmutation"
level: 1
concentration: false
casting_time: "1 réaction, que vous effectuez quand vous-même ou une créature située dans un rayon de 18 mètres tombe soudain"
duration: "1 minute"
range: "18 mètres"
components:
  verbal: true
  somatic: false
  material: true
  materials: "une petite plume ou un peu de duvet"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
```
Choisissez jusqu'à cinq créatures à portée en train de chuter. La vitesse de chute de chacune passe à 18 mètres par round jusqu'à la fin du sort. Si une créature atterrit avant la fin du sort, elle ne subit pas de dégât de chute et se reçoit sur ses pieds, le sort se terminant alors pour elle.




### Mains brûlantes
```yml
title: "Mains brûlantes"
description: "Cône de flammes infligeant 3d6 dégâts de feu."
school: "Évocation"
level: 1
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "personnelle (cône de 4,50 mètres)"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Alors que vous vous tenez les doigts écartés en éventail et les pouces l'un contre l'autre, une mince nappe de feu s'étend depuis vos mains tendues. Chaque créature située dans un cône de 4,50 mètres doit faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. Celles qui échouent reçoivent 3d6 dégâts de feu, les autres la moitié seulement.

Le feu embrase tous les objets inflammables de la zone, à moins que quelqu'un ne les porte ou ne les transporte.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, les dégâts augmentent de 1d6 par niveau au-delà du niveau 1.




### Nappe de brouillard
```yml
title: "Nappe de brouillard"
description: "Crée un brouillard dans lequel la visibilité est nulle."
school: "Invocation"
level: 1
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 heure"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Rôdeur
```
Vous créez une sphère de brouillard de 6 mètres de rayon centrée sur un point à portée. La sphère s'étend en contournant les angles et, dans la zone qu'elle occupe, la visibilité est nulle. Le brouillard persiste pendant toute la durée du sort ou jusqu'à ce qu'un vent modéré ou plus violent (soufflant au moins à 15 kilomètres par heure) le disperse.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, le rayon de la sphère augmente de 6 mètres par niveau au-delà du niveau 1.





### Projectile magique
```yml
title: "Projectile magique"
description: "Trois flèches touchent automatiquement et infligent 1d4+1 dégâts."
school: "Évocation"
level: 1
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous créez trois fléchettes faites d'énergie magique brillante. Chacune touche une créature de votre choix, située à portée et dans votre champ de vision. Une fléchette inflige 1d4+1 dégâts de force à la cible. Toutes les fléchettes frappent leur cible en même temps, sachant que vous pouvez toutes les diriger contre une seule et même créature ou les répartir entre plusieurs.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, le sort crée une fléchette de plus par niveau au-delà du niveau 1.




### Repli expéditif
```yml
title: "Repli expéditif"
description: "Le PJ peut utiliser l'action <em>se précipiter</em> en action bonus."
school: "Transmutation"
level: 1
concentration: true
casting_time: "1 action bonus"
duration: "jusqu'à 10 minutes"
range: "personnelle"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Ce sort vous permet de vous déplacer à une vitesse incroyable. Vous pouvez utiliser l'action [_se précipiter_](/combattre/#se-precipiter) quand vous le lancez, puis par une action bonus à chacun de vos tours jusqu'à ce que le sort se termine.




### Sang du démon
```yml
title: "Sang du démon"
description: "La cible subit 1d6 dégâts d'acide à chaque tour."
school: "Nécromancie"
level: 1
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "contact"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une fiole d'un mélange de sang et d'acide"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous contaminez le sang d'une créature vivante que vous touchez. Vous effectuez une attaque de sort au contact. Si elle est réussie, le sang de la cible devient corrosif, lui infligeant 1d6 dégâts d'acide à chacun de vos tours. Si la cible réussit un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution, les dégâts sont ignorés pour ce tour.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de sort de niveau 2 ou supérieur, les dégâts augmentent de 1d6 pour chaque niveau au-delà du niveau 1.





### Saut
```yml
title: "Saut"
description: "La cible voit sa distance de saut triplée."
school: "Transmutation"
level: 1
concentration: false
casting_time: "1 action"
duration: "1 minute"
range: "contact"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une patte arrière de sauterelle"
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Rôdeur
```
Vous touchez une créature et triplez sa distance de saut jusqu'à ce que le sort se termine.



### Simulacre de vie
```yml
title: "Simulacre de vie"
description: "Le PJ gagne 1d4+4 points de vie temporaires."
school: "Nécromancie"
level: 1
concentration: false
casting_time: "1 action"
duration: "1 heure"
range: "personnelle"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une petite quantité d'alcool ou de spiritueux"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous renforcez votre corps avec un ersatz de vie et gagnez 1d4+4 points de vie temporaires pendant la durée du sort.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, vous gagnez 5 points de vie temporaires supplémentaires par niveau au-delà du niveau 1.





### Sommeil
```yml
title: "Sommeil"
description: "Rend inconscientes les cibles dans un rayon de 6 mètres."
school: "Enchantement"
level: 1
concentration: false
casting_time: "1 action"
duration: "1 minute"
range: "27 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une pincée de sable fin, des pétales de rose ou un criquet"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
```
Ce sort plonge quelques créatures dans un sommeil magique. Lancez 5d8. Le total indique le nombre de points de vie de créatures que le sort affecte. Les créatures qui se trouvent dans un rayon de 6 mètres autour d'un point de votre choix situé à portée sont affectées dans l'ordre croissant de leur total actuel de points de vie (en ignorant les créatures <RT l="inconscientes" t="inconscient"/>).

Chaque créature affectée par le sort tombe [_inconsciente_](/gerer-la-sante-du-personnage/#inconscient), en commençant par celle qui possède actuellement le moins de vie. Elle reste ainsi jusqu'à la fin de la durée du sort, jusqu'à ce qu'elle subisse des dégâts ou jusqu'à ce que quelqu'un utilise son action pour la réveiller en la secouant ou en la giflant. Soustrayez le nombre de points de vie de la créature endormie du total auquel vous avez droit avant de passer à la suivante, c'est-à-dire celle qui a le moins de points de vie après elle. Le nombre de points de vie de la créature doit être égal ou inférieur au total vous restant, sinon le sort n'affecte pas la créature.

Ce sort reste sans effet sur les morts-vivants et les créatures qui ne peuvent être <RT l="charmées" t="charme"/>.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, lancez 2d8 de plus par niveau au-delà du niveau 1.





### Strangulation
```yml
title: "Strangulation"
description: "Le PJ étrangle une cible à distance, lui inflige 1d6 dégâts et l'<em>entrave</em>."
school: "Invocation"
level: 1
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "9 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous tendez le bras en direction de votre cible et, de votre main, vous mimez son étranglement. Faites une attaque de sort à distance. En cas de réussite, la cible subit 1d6 points de dégâts contondants et elle doit faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Force ou être [_entravée_](/gerer-la-sante-du-personnage/#entrave). Si le [jet d'attaque](/combattre/#jets-d-attaque) initial était un succès, à chacun de vos tours pendant la durée du sort, vous pouvez utiliser votre action pour lui infliger automatiquement les mêmes dégâts et l'obliger à faire un nouveau [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Force. Si vous faites quoi que ce soit d'autre (vous pouvez toutefois parler), le sort prend fin. Le sort prend aussi fin si la cible passe hors de portée ou en dehors de votre champ de vision.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 3, vous infligez 2d6 points de dégât par round. Vous augmentez les dégâts de 1d6 supplémentaires par tranche de 2 niveaux de plus (jusqu'à 5d6 au niveau 9).




### Vague tonnante
```yml
title: "Vague tonnante"
description: "Les cibles subissent 2d8 dégâts et sont repoussées de 3 mètres."
school: "Évocation"
level: 1
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "personnelle (cube de 4,50 mètres)"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Barde
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
```
Une vague de force tonnante émane de vous. Chaque créature située dans un cube de 4,50 mètres d'arête partant de vous doit faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution. Les créatures qui échouent subissent 2d8 dégâts de tonnerre et sont bousculées de 3 mètres en face de vous. Les autres subissent seulement la moitié des dégâts et ne sont pas bousculées.

De plus, les objets qui ne sont pas arrimés et se trouvent entièrement englobés dans la zone affectée sont automatiquement éloignés de 3 mètres à l'opposé de vous. Le sort émet un grondement de tonnerre qui s'entend dans un rayon de 90 mètres.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, les dégâts augmentent de 1d8 par niveau au-delà du premier.





## Niveau 2

### Agrandir/rétrécir
```yml
title: "Agrandir/rétrécir"
description: "Augmente ou diminue la taille de la cible."
school: Transmutation
level: 2
classes:
  - Ensorceleur/Sorcelame
  - Magicien
concentration: true
casting_time: "1 action"
range: "9 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une pincée de limaille de fer"
duration: "jusqu'à 1 minute"
ritual: false
```
Vous agrandissez ou rétrécissez une créature ou un objet situé à portée et dans votre champ de vision pendant toute la durée du sort. Choisissez soit une créature, soit un objet qui n'est ni porté ni transporté. Si la cible n'est pas consentante, elle a droit à un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution. Si elle le réussit, le sort est sans effet. Si la cible est une créature, tout ce qu'elle porte et tout ce qu'elle transporte change de taille avec elle. En revanche, si elle lâche un objet, il reprend sa taille normale sur-le-champ.

**Agrandir**. La cible double dans toutes les dimensions, et son poids est multiplié par huit. Cette croissance augmente sa catégorie de taille d'un cran, de M à G par exemple. Si la cible n'a pas assez de place pour doubler de volume, elle atteint la taille maximale possible dans l'espace dont elle dispose. Elle bénéficie d'un [_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors des tests de Force et des jets de sauvegarde de Force jusqu'à la fin du sort. Les armes de la cible grandissent pour s'adapter à sa nouvelle taille. Tant qu'elles sont ainsi agrandies, elles infligent 1d4 dégâts de plus.

**Rétrécir**. La cible réduit de moitié dans toutes les dimensions et son poids est divisé par huit. Ce rétrécissement réduit sa catégorie de taille d'un cran, de M à P par exemple. La cible subit un [_désavantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors des tests de Force et des jets de sauvegarde de Force jusqu'à la fin du sort. Les armes de la cible rétrécissent pour s'adapter à sa nouvelle taille. Tant qu'elles sont ainsi réduites, elles infligent 1d4 dégâts de moins (avec un minimum de 1 dégât).




### Amélioration de caractéristique
```yml
title: "Amélioration de caractéristique"
description: "Une des caractéristiques de la cible est augmentée."
school: Transmutation
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 heure"
range: "contact"
components:
  verbal: true
  somatic: true
  material: true
  materials: "des poils ou des plumes venant d'un animal"
classes:
  - Barde
  - Clerc
  - Druide
  - Ensorceleur/Sorcelame
ritual: false
```
Vous touchez une créature pour lui accorder une amélioration magique. Choisissez l'un des effets suivants, dont la cible bénéficiera jusqu'à la fin du sort.

**Endurance de l'ours**. La cible a l'[_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors des tests de Constitution. Elle gagne aussi 2d6 points de vie temporaires qui disparaissent quand le sort se termine.

**Force du taureau**. La cible bénéficie d'un [_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors des tests de Force et le poids qu'elle peut porter est doublé.

**Grâce du chat**. La cible a l'[_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors des tests de Dextérité. De plus, elle ne subit pas de dégât quand elle chute de 6 mètres ou moins, à condition qu'elle ne soit pas neutralisée.

**Splendeur de l'aigle**. La cible bénéficie d'un [_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors des tests de Charisme.

**Ruse du renard**. La cible a l'[_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors des tests d'Intelligence.

**Sagesse du hibou**. La cible a l'[_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors des tests de Sagesse.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, vous pouvez prendre une créature de plus pour cible par niveau au-delà du niveau 2.









### Bourrasque
```yml
title: "Bourrasque"
description: "Crée un vent violent qui ralentit et <em>repousse</em> les créatures."
school: "Évocation"
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "personnelle (ligne de 18 mètres)"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une graine de légume"
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
```
Une zone de fort vent de 18 mètres de long sur 3 mètres de large souffle depuis votre position dans la direction de votre choix pendant toute la durée du sort. Chaque créature qui débute son tour dans la zone doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Force, sans quoi elle est rejetée de 4,50 mètres à l'opposé de vous, dans la direction du vent.

Une créature qui se trouve dans la zone doit dépenser 60 centimètres de mouvement pour se rapprocher de vous de 30 centimètres.

La bourrasque disperse les gaz et les vapeurs et éteint les bougies, les torches et autres flammes nues similaires dans la zone. Les flammes protégées, par une lanterne par exemple, s'agitent follement et ont 50 % de chance de s'éteindre.

Vous pouvez changer la direction dans laquelle souffle la bourrasque au moyen d'une action bonus à chacun de vos tours jusqu'à la fin du sort.





### Briser
```yml
title: "Briser"
description: "Inflige 3d8 dégâts dans un rayon de 3 mètres, y compris aux objets non magiques."
school: "Évocation"
level: 2
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un éclat de mica"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Un bruit retentit soudain avec une intensité douloureuse, à partir d'un point situé à portée. Chaque créature située dans une sphère de 3 mètres de rayon centrée sur ce point doit faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution. Les créatures qui le ratent subissent 3d8 dégâts de tonnerre, les autres la moitié seulement. Une créature faite de matière inorganique, comme de la pierre, du cristal ou du métal subit un [_désavantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) sur ce [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde).

Un objet non magique que personne ne porte ni ne transporte subit aussi ces dégâts s'il se trouve dans la zone du sort.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, les dégâts augmentent de 1d8 par niveau au-delà du niveau 2.








### Cécité/Surdité
```yml
title: "Cécité/Surdité"
description: "Rend un ennemi <em>sourd</em> ou <em>aveugle</em>."
school: "Nécromancie"
level: 2
concentration: false
casting_time: "1 action"
duration: "1 minute"
range: "9 mètres"
components:
  verbal: true
  somatic: false
  material: false
ritual: false
classes:
    - Barde
    - Clerc
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous pouvez rendre un ennemi sourd ou aveugle. Choisissez une créature autre que vous qui se situe à portée et dans votre champ de vision. Elle doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution. Si elle échoue, elle est soit [_aveuglée_](/gerer-la-sante-du-personnage/#aveugle), soit [_assourdie_](/gerer-la-sante-du-personnage/#assourdi) (à vous de choisir) pendant toute la durée du sort. Elle a droit à un nouveau [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution à la fin de chacun de ses tours, le sort se terminant si elle le réussit.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, vous pouvez viser une créature de plus par niveau au-delà du niveau 2.



### Déblocage
```yml
title: "Déblocage"
description: "Permet d'ouvrir une serrure, supprime temporairement <em>verrou magique</em>."
school: "Transmutation"
level: 2
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "18 mètres"
components:
  verbal: true
  somatic: false
  material: false
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
```
Choisissez un objet situé à portée et dans votre champ de vision. Ce peut être une porte, une boîte, un coffre, des menottes, un cadenas ou un autre objet disposant d'un système de fermeture ordinaire ou magique.

Une cible fermée par une serrure ordinaire, coincée ou bloquée par une barre se déverrouille ou se débloque. Si l'objet a plusieurs serrures, le sort en ouvre une seule. Si vous visez une cible fermée par un <ST s="verrou-magique"/>, ce dernier est supprimé pendant 10 minutes, au cours desquelles on peut ouvrir et fermer la cible normalement.

Quand vous lancez le sort, un cliquetis émane de l'objet et retentit si fort qu'on l'entend dans un rayon de 90 mètres.



### Détection des pensées
```yml
title: "Détection des pensées"
description: "Permet de lire les pensées de certaines créatures."
school: "Divination"
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "personnelle"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une pièce de cuivre"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
```
Pendant toute la durée du sort, vous parvenez à lire les pensées de certaines créatures. Quand vous lancez ce sort, puis en tant qu'action à votre tour jusqu'à la fin du sort, vous pouvez focaliser vos pensées sur une créature située à moins de 9 mètres dans votre champ de vision. Si elle dispose d'une Intelligence de 3 ou moins ou ne parle aucune langue, elle n'est pas affectée.

Au départ, vous découvrez les pensées superficielles de la créature, c'est-à-dire ce qu'elle a à l'esprit à ce moment-là. Par une action, vous pouvez porter votre attention sur les pensées d'une autre créature ou tenter de vous enfoncer plus profondément dans l'esprit de celle que vous sondez actuellement. Dans ce cas, cette créature doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse. Si elle réussit, le sort se termine. Sinon, vous avez un aperçu de son mode de raisonnement (le cas échéant), de son état émotionnel ou de ce qui occupe une place importante dans son esprit (par exemple, quelque chose qui l'inquiète fortement, qu'elle aime, qu'elle déteste...). Dans les deux cas, la cible sait que vous sondez son esprit et, à moins que vous ne tourniez votre attention vers une autre créature, votre cible peut utiliser son action à son tour pour faire un test d'Intelligence opposé au vôtre. Si elle réussit, le sort se termine.

Les questions directement posées à l'oral à une cible orientent naturellement le cours de ses pensées, ce sort est donc particulièrement utile lors d'un interrogatoire.

Vous pouvez aussi utiliser ce sort pour détecter la présence de créatures intelligentes que vous ne voyez pas. Vous pouvez chercher les pensées qui se trouvent dans un rayon de 9 mètres autour de vous au moment où vous lancez ce sort ou bien par une action tandis que le sort est actif. Le sort peut franchir des obstacles, mais il est arrêté par 60 centimètres de roche, 2,5 centimètres de métal autre que le plomb ou une mince feuille de plomb. Vous ne pouvez pas repérer les créatures dotées d'une Intelligence de 3 ou moins, ni celles qui ne parlent aucune langue.

Une fois que vous avez ainsi détecté la présence d'une créature, vous pouvez lire ses pensées pendant le reste de la durée du sort, comme expliqué plus haut, même si vous ne la voyez pas, mais elle doit tout de même se trouver à portée.




### Flou
```yml
title: "Flou"
description: "Les créatures ont un <em>désavantage</em> pour attaquer le PJ."
school: "Illusion"
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "personnelle"
components:
  verbal: true
  somatic: false
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
```
Votre corps devient flou, il ondule et vacille comme une flamme aux yeux d'autrui. Pendant toute la durée du sort, les créatures subissent un _désavantage_ lorsqu'elles font un [jet d'attaque](/combattre/#jets-d-attaque) contre vous. Un attaquant est immunisé contre cet effet s'il ne se repose pas sur sa vue, s'il dispose de vision aveugle, par exemple, ou s'il peut percer les illusions à jour avec vision parfaite.






### Image miroir
```yml
title: "Image miroir"
description: "Crée trois répliques illusoires du PJ qui peuvent subir les attaques à sa place."
school: "Illusion"
level: 2
concentration: false
casting_time: "1 action"
duration: "1 minute"
range: "personnelle"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Trois répliques illusoires de votre personne apparaissent dans votre emplacement. Jusqu'à la fin du sort, ces répliques se déplacent en même temps que vous et imitent toutes vos actions, changeant de position de manière à ce qu'il soit impossible de savoir quelles versions de vous sont des images et quelle version est réelle. Vous pouvez utiliser une action pour révoquer les répliques illusoires.

Pendant toute la durée du sort, chaque fois qu'une créature vous prend pour cible d'une attaque, vous devez lancer 1d20 pour savoir si l'attaque touche votre personne ou l'un de vos doubles. Si vous avez trois répliques, vous devez obtenir 6 ou plus pour que l'attaque touche une réplique. Si vous n'en avez plus que deux, vous devez faire 8 ou plus, et si vous n'en avez plus qu'une, vous devez faire 11 ou plus.

Chaque réplique possède une CA de 10 + votre modificateur de Dextérité. Si l'attaque touche une réplique, elle la détruit. Le seul moyen de détruire une réplique est de l'atteindre avec une attaque, car elle ignore tous les autres effets et dégâts. Le sort se termine si les trois répliques sont détruites.

Une créature n'est pas affectée par ce sort si elle ne voit pas, si elle se sert d'un mode de perception autre que la vue (comme la vision aveugle) ou encore si elle perçoit les illusions comme telles, avec vision parfaite, par exemple.*




### Immobiliser un humanoïde
```yml
title: "Immobiliser un humanoïde"
description: "La cible est <em>paralysée</em>."
school: "Enchantement"
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un petit morceau de fer bien droit"
ritual: false
classes:
    - Barde
    - Clerc
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Choisissez un humanoïde situé à portée et dans votre champ de vision. Il doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse, sans quoi il est [_paralysé_](/gerer-la-sante-du-personnage/#paralyse) pour toute la durée du sort. À la fin de chacun de ses tours, la cible a droit à un nouveau [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse. Si elle le réussit, le sort se termine.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, vous pouvez viser un humanoïde de plus par niveau au-delà du niveau 2. Les humanoïdes visés doivent se trouver à 9 mètres ou moins les uns des autres au moment où vous lancez le sort.






### Invisibilité
```yml
title: "Invisibilité"
description: "La cible est <em>invisible</em>. Le sort prend fin si la cible attaque ou lance un sort."
school: "Illusion"
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 heure"
range: "contact"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un cil enrobé de gomme arabique"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
La créature que vous touchez devient [_invisible_](/gerer-la-sante-du-personnage/#invisible) jusqu'à la fin du sort. Tout ce qu'elle porte et transporte reste [_invisible_](/gerer-la-sante-du-personnage/#invisible) tant qu'elle le garde sur elle. Le sort se termine si la cible attaque ou lance un sort.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, vous pouvez viser une créature de plus par niveau au-delà du niveau 2.





### Lévitation
```yml
title: "Lévitation"
description: "La cible s'élève à 6 mètres du sol."
school: "Transmutation"
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 10 minutes"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "soit une petite boucle de cuir, soit un bout de fil de métal doré formant la silhouette d'une cuillère au long manche"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Une créature ou un objet situé à portée et dans votre champ de vision s'élève à la verticale à une hauteur de 6 mètres et reste suspendu là pendant toute la durée du sort. Ce dernier peut soulever une cible d'au maximum 250 kilogrammes. Si la créature visée n'est pas consentante, elle doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution pour éviter d'être affectée par le sort.

La cible peut se déplacer uniquement en se propulsant ou en se tractant, en prenant appui sur un objet fixe ou une surface à proximité (comme un mur ou un plafond). Elle se meut alors comme si elle était en pleine escalade. Quand vient votre tour, vous pouvez modifier l'altitude de la cible d'un maximum de 6 mètres dans la direction de votre choix. Si vous êtes la cible, vous pouvez monter ou descendre lors de votre déplacement. En dehors de cela, vous devez dépenser une action pour déplacer la cible qui doit rester à portée du sort.

Si la cible est encore en l'air quand le sort se termine, elle flotte délicatement jusqu'au sol.






### Modifier son apparence
```yml
title: "Modifier son apparence"
description: "Le PJ transforme tout ou partie de son corps."
school: "Transmutation"
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 heure"
range: "personnelle"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
```
Vous revêtez une forme différente. Quand vous lancez ce sort, choisissez l'une des options suivantes, dont les effets dureront aussi longtemps que le sort. Tant qu'il est actif, vous pouvez utiliser une action pour mettre un terme à une option afin de bénéficier d'une autre.

**Adaptation aquatique**. Vous adaptez votre corps à un environnement aquatique, générant des branchies et des palmures entre vos doigts. Vous pouvez respirer sous l'eau et gagnez une vitesse de nage égale à votre vitesse de marche.

**Armes naturelles**. Vous acquérez des griffes, des crocs, des épines, des cornes ou une autre arme naturelle de votre choix. Vos attaques à mains nues infligent 1d6 dégâts contondants, perforants ou tranchants, comme il sied à l'arme naturelle que vous avez choisie et vous maîtrisez automatiquement les attaques à mains nues. Enfin, votre arme naturelle est de nature magique et vous disposez d'un bonus de +1 aux jets d'attaque et de dégâts quand vous l'utilisez.

**Changer d'apparence**. Vous modifiez votre apparence et choisissez votre taille, votre poids, vos traits, le son de votre voix, la longueur de vos cheveux, votre pigmentation, et toute caractéristique distinctive désirée. Vous pouvez vous faire passer pour un membre d'une autre race, mais vos caractéristiques ne changent pas. Vous ne pouvez pas vous faire passer pour une créature d'une catégorie de taille différente de la vôtre, et votre silhouette générale doit rester la même (par exemple, si vous êtes un bipède, vous ne pouvez pas utiliser ce sort pour prendre l'apparence d'un quadrupède). À tout moment lors de la durée du sort, vous pouvez dépenser une action pour modifier de nouveau votre apparence de cette manière.



### Offrande inéluctable
```yml
title: "Offrande inéluctable"
description: "Force la cible à vous donner l'objet qu'elle tient en main."
school: "Enchantement"
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Une créature vivante à portée et dans votre champ de vision doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse sous peine de se sentir soudainement obligée de vous donner ce qu'elle tient au moment où vous lancez le sort. Dès son tour, la cible se rapproche aussi près que possible de vous et vous tend l'objet. Pour toute la durée du sort, la cible fait en sorte de protéger l'objet qu'elle doit vous donner et ne peut donc pas s'en servir pour attaquer ni pour se défendre et subit par ailleurs d'un [_désavantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) sur ses jets d'attaques.

Le sort prend fin si vous ou vos alliés blessez la cible ou lui lancez un sort néfaste, ou si vous vous trouvez au-delà de la portée du sort.






### Ombres imaginaires
```yml
title: "Ombres imaginaires"
description: "La cible subit un <em>désavantage</em> à toutes ses actions."
school: "Illusion"
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un morceau de charbon"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
```
Vous désignez une cible à portée et dans votre champ de vision. Vous créez des images fantasmagoriques cauchemardesques dans son esprit. La victime doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) d'Intelligence. En cas d'échec, elle perçoit des silhouettes d'ombres qui l'assaillent, ce qui lui inflige un [_désavantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) à toutes ses actions pendant la durée du sort.

**À plus haut niveau**. Lorsque vous lancez ce sort en utilisant un emplacement de sort de niveau 5 ou supérieur, le sort persiste jusqu'à la fin de sa durée normale sans nécessiter de concentration.




### Pas brumeux
```yml
title: "Pas brumeux"
description: "Téléportation à 9 mètres pour une action bonus."
school: "Invocation"
level: 2
concentration: false
casting_time: "1 action bonus"
duration: "instantanée"
range: "personnelle"
components:
  verbal: true
  somatic: false
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Vous êtes brièvement entouré d'une brume argentée et vous vous téléportez sur un maximum de 9 mètres jusqu'à un emplacement inoccupé situé dans votre champ de vision.




### Pattes d'araignée
```yml
title: "Pattes d'araignée"
description: "La cible peut marcher aux murs et aux plafonds."
school: "Transmutation"
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 heure"
range: "contact"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une goutte de bitume et une araignée"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Jusqu'à la fin du sort, une créature consentante que vous touchez devient capable de se déplacer sur les surfaces verticales, et même au plafond la tête en bas, tout en gardant les mains libres. La cible bénéficie aussi d'une vitesse d'escalade égale à sa vitesse de marche.



### Rayon ardent
```yml
title: "Rayon ardent"
description: "Projette trois rayons qui infligent 2d6 dégâts."
school: "Évocation"
level: 2
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous créez trois rayons de feu et les projetez sur des cibles à portée. Vous pouvez les diriger contre une même cible ou contre des cibles différentes. Faites une attaque de sort à distance pour chaque rayon. Si vous touchez, la cible reçoit 2d6 dégâts.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, vous créez un rayon de plus par niveau au-delà du niveau 2.





### Stalagmites fulgurantes
```yml
title: "Stalagmites fulgurantes"
description: "4d4 dommages dans un carré de 3  mètres et cibles <em>entravées</em>."
school: "Invocation"
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "30 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous faites jaillir du sol des stalagmites de pierre d'une hauteur de 3 mètres dans une zone carrée de 3 mètres d'arête à portée du sort. Si elles atteignent le plafond avant d'atteindre leur taille maximale, les stalagmites cessent de grandir. Chaque créature dans la zone doit effectuer une sauvegarde de Dextérité. Une créature volant à moins de 3 mètres du sol bénéficie d'un [_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) sur ce jet. En cas d'échec, les stalagmites infligent 4d4 dégâts perforants et la cible se retrouve [_entravée_](/gerer-la-sante-du-personnage/#entrave) entre les stalagmites jusqu'à la fin du sort. En cas de succès, elle ne subit que la moitié des dégâts et est libre ses mouvements. Une cible [_entravée_](/gerer-la-sante-du-personnage/#entrave) par les stalagmites peut utiliser une action pour effectuer une sauvegarde de Force. En cas de réussite, la créature se libère, mais subit 1d6 dégâts contondants. Pour la durée du sort, le terrain où se trouvent les stalagmites est considéré comme difficile.

**À plus haut niveau**. Lorsque vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, les dégâts perforants augmentent de 2d4 pour chaque niveau au-delà du niveau 2.



### Suggestion
```yml
title: "Suggestion"
description: "Impose la conduite à suivre à la cible."
school: "Enchantement"
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 8 heures"
range: "9 mètres"
components:
  verbal: true
  somatic: false
  material: true
  materials: "une langue de serpent et soit un rayon de miel, soit une goutte d'huile d'olive"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Vous visez une créature située à portée et dans votre champ de vision et à même de vous entendre et de vous comprendre. Vous l'influencez par magie de façon à ce qu'elle suive la conduite que vous lui proposez (en seulement une phrase ou deux). Les créatures qui ne peuvent être _charmées_ sont immunisées contre ce sort. Vous devez formuler votre suggestion de manière à ce que la conduite à tenir semble tout à fait raisonnable. Si vous demandez à une créature de se poignarder, de se laisser tomber sur une lance, de s'immoler ou d'accomplir n'importe quelle action à l'évidence néfaste, le sort se termine automatiquement.

La cible doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse, sans quoi elle fait de son mieux pour suivre la conduite que vous lui avez suggérée et cela peut continuer pendant toute la durée du sort. Si l'action suggérée peut se finir plus rapidement, le sort se termine quand la cible a accompli ce que vous lui aviez demandé.

Vous pouvez spécifier des conditions qui déclenchent une conduite spéciale pendant la durée du sort. Par exemple, vous pouvez suggérer à un chevalier de donner son cheval de guerre au premier mendiant qu'il rencontre. Si les conditions ne sont pas remplies avant la fin du sort, la cible n'accomplit pas l'action.

Si vous (ou l'un de vos compagnons) blessez une créature affectée par ce sort, le sort se termine.





### Ténèbres
```yml
title: "Ténèbres"
description: "Sphère de 4,50 mètres plongée dans le noir complet."
school: "Évocation"
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 10 minutes"
range: "18 mètres"
components:
  verbal: true
  somatic: false
  material: true
  materials: "des poils de chauve-souris et une goutte de poix ou un bout de charbon"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Des ténèbres magiques se répandent depuis un point de votre choix situé à portée, jusqu'à englober une sphère de 4,50 mètres de rayon. Les ténèbres s'étendent en franchissant tout angle éventuel. La vision dans le noir d'une créature ne suffit pas à percer ces ténèbres et les lumières non-magiques se révèlent incapables de les éclairer.

Si le point que vous avez choisi est un objet en votre possession ou un objet qui n'est ni porté ni transporté par autrui, les ténèbres émanent de l'objet et se déplacent avec lui. Il suffit de recouvrir complètement l'objet affecté avec un objet opaque, comme un bol ou un heaume, pour bloquer les ténèbres.

Si une partie de la zone affectée par ce sort chevauche une zone de lumière issue d'un sort de niveau 2 ou moins, elle dissipe le sort de lumière.



### Toile d'araignée
```yml
title: "Toile d'araignée"
description: "Cube de 6 mètres dans lequel les créatures sont <em>entravées</em>."
school: "Invocation"
level: 2
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 heure"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un bout de toile d'araignée"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous invoquez une masse de toiles d'araignées épaisses et collantes en un point de votre choix situé à portée. Pendant toute la durée du sort, les toiles occupent un cube de 6 mètres d'arête centré sur le point choisi. Elles forment un terrain difficile à la visibilité réduite.

Si les toiles ne sont pas ancrées entre deux éléments solides, comme des murs ou des arbres, ou disposées en couches sur le sol, le plafond ou un mur, elles s'effondrent sur elles-mêmes et le sort se termine au début de votre prochain tour. Des toiles disposées en couches superposées sur une surface plane s'accumulent sur une épaisseur de 1,50 mètre.

Chaque créature qui commence son tour dans les toiles ou qui y pénètre lors de son tour doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité, ou être [_entravée_](/gerer-la-sante-du-personnage/#entrave) tant qu'elle reste dans les toiles ou jusqu'à ce qu'elle se libère.

Une créature [_entravée_](/gerer-la-sante-du-personnage/#entrave) par les toiles peut utiliser son action pour effectuer un test de Force contre le DD du [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de votre sort. Si elle le réussit, elle n'est plus [_entravée_](/gerer-la-sante-du-personnage/#entrave).

Les toiles sont inflammables. Un cube de toiles de 1,50 mètre d'arête exposé au feu brûle en 1 round, infligeant 2d4 dégâts de feu à toute créature qui commence son tour dans les flammes.





### Vision dans le noir
```yml
title: "Vision dans le noir"
description: "La cible bénéficie d'une vision dans le noir à 18 mètres."
school: "Transmutation"
level: 2
concentration: false
casting_time: "1 action"
duration: "8 heures"
range: "contact"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une pincée de carotte séchée ou une agate"
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Rôdeur
```
Vous touchez une créature consentante pour lui permettre de voir dans le noir. Pendant toute la durée du sort, elle bénéficie de la vision dans le noir à une distance de 18 mètres.




### Voir l'invisible
```yml
title: "Voir l'invisible"
description: "Le PJ peut voir les créatures et objets <em>invisibles</em> et observer le plan éthéré."
school: "Divination"
level: 2
concentration: false
casting_time: "1 action"
duration: "1 heure"
range: "personnelle"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une pincée de talc et un saupoudrage de poudre d'argent"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
```
Pendant toute la durée du sort, vous voyez les créatures et les objets [_invisibles_](/gerer-la-sante-du-personnage/#invisible) comme s'ils étaient bien visibles et vous pouvez aussi observer le plan éthéré. Les créatures et les objets éthérés vous apparaissent comme des silhouettes translucides et fantomatiques.






## Niveau 3

### Boule de feu
```yml
title: "Boule de feu"
description: "Explosion de 6 mètres de rayon qui inflige 8d6 dégâts de feu."
school: "Évocation"
level: 3
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "45 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une petite boule de guano de chauve-souris et du soufre"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Une traînée luisante part de votre doigt tendu et file vers un point de votre choix situé à portée et dans votre champ de vision, où elle explose dans une gerbe de flammes grondantes. Chaque créature située dans une sphère de 6 mètres de rayon centrée sur ce point doit faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. Celles qui échouent subissent 8d6 dégâts de feu, les autres la moitié seulement.

Le feu s'étend en contournant les angles. Il embrase les objets inflammables de la zone, à moins que quelqu'un ne les porte ou ne les transporte.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, les dégâts augmentent de 1d6 par niveau au-delà du niveau 3.





### Clairvoyance
```yml
title: "Clairvoyance"
description: "Le PJ peut voir ou entendre par un organe sensoriel invisible à 1,5 kilomètre."
school: "Divination"
level: 3
concentration: true
casting_time: "10 minutes"
duration: "jusqu'à 10 minutes"
range: "1,5 kilomètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un focaliseur d'une valeur minimale de 100 po, soit une corne incrustée de pierreries pour l'ouïe, soit un œil de verre pour la vue"
ritual: false
classes:
    - Barde
    - Clerc
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
```
Vous créez un organe sensoriel [_invisible_](/gerer-la-sante-du-personnage/#invisible) à portée dans un endroit qui vous est familier (un endroit où vous vous êtes déjà rendu ou que vous avez déjà vu) ou dans un endroit évident qui ne vous est pas familier (comme de l'autre côté d'une porte, derrière un angle de mur, dans un bosquet...). L'organe reste là pendant toute la durée du sort. Il est impossible de l'attaquer ou d'interagir avec.

Vous choisissez la vue ou l'ouïe au moment où vous lancez le sort. Vous pouvez alors utiliser le sens choisi à travers l'organe comme si vous occupiez son emplacement. Vous pouvez dépenser une action pour passer de la vue à l'ouïe ou inversement.

Une créature capable de voir l'organe sensoriel (en bénéficiant par exemple de voir l'[_invisible_](/gerer-la-sante-du-personnage/#invisible) ou de _vision parfaite_) le perçoit comme un orbe lumineux intangible de la taille de votre poing.





### Clignotement
```yml
title: "Clignotement"
description: "Le PJ passe à chaque tour du plan matériel au plan éthéré et vice-versa."
school: "Transmutation"
level: 3
concentration: false
casting_time: "1 action"
duration: "1 minute"
range: "personnelle"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Pendant toute la durée du sort, vous lancez 1d20 à la fin de chacun de vos tours. Sur un 11 ou plus, vous disparaissez de votre plan d'existence actuel et apparaissez sur le plan éthéré (si vous vous trouviez déjà là, le sort échoue et l'incantation est gaspillée). Au début de votre tour suivant et quand le sort se termine alors que vous vous trouvez sur le plan éthéré, vous retournez sur un emplacement inoccupé de votre choix que vous pouvez voir dans un rayon de 3 mètres autour de l'emplacement dont vous avez disparu. S'il n'y a pas d'emplacement disponible dans ce rayon, vous apparaissez dans l'espace inoccupé le plus proche (choisi au hasard s'il y en a plusieurs à égale distance). Vous pouvez révoquer ce sort par une action.

Tant que vous êtes sur le plan éthéré, vous voyez et entendez ce qui se passe sur le plan d'où vous venez, qui apparaît sous forme d'ombres grises, mais votre vision ne porte pas au-delà de 18 mètres. Vous pouvez seulement affecter des créatures se trouvant sur le plan éthéré et elles sont les seules à pouvoir vous affecter. Les créatures qui ne se trouvent pas sur ce plan ne peuvent ni vous percevoir, ni interagir avec vous, à moins qu'elles ne disposent d'un pouvoir le leur permettant.




### Contresort
```yml
title: "Contresort"
description: "Réaction qui permet au PJ d'empêcher le lancement d'un sort."
school: "Abjuration"
level: 3
concentration: false
casting_time: "1 réaction à utiliser quand vous voyez une créature située dans un rayon de 18 mètres autour de vous lancer un sort"
duration: "instantanée"
range: "18 mètres"
components:
  verbal: false
  somatic: true
  material: false
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous tentez d'interrompre une créature en pleine incantation. Si elle essayait de lancer un sort de niveau 3 ou moins, il échoue et reste sans effet. Si le sort est de niveau 4 ou plus, faites un [test de caractéristique](/utiliser-les-caracteristiques/#tests-de-caracteristique) en utilisant votre caractéristique d'incantation. Le DD est de 10 + le niveau du sort. Si vous réussissez, le sort de la créature échoue et reste sans effet.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, le sort à interrompre est automatiquement sans effet s'il est d'un niveau égal ou inférieur à celui de l'emplacement de sort utilisé.




### Dissipation de la magie
```yml
title: "Dissipation de la magie"
description: "Annule un effet magique ou un sort."
school: "Abjuration"
level: 3
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Barde
    - Clerc
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Paladin
    - Sorcier

source: "Manuel des règles"
---
Choisissez une créature, un objet ou un effet magique à portée. Tout sort de niveau 3 ou inférieur qui l'affecte se termine. Si la cible est affectée par un sort de niveau 4 ou plus, faites un [test de caractéristique](/utiliser-les-caracteristiques/#tests-de-caracteristique) en utilisant votre caractéristique d'incantation. Le DD est de 10 + niveau du sort. Ce dernier se termine si vous réussissez votre test.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, vous mettez automatiquement un terme à un sort affectant la cible quand le niveau de ce sort est égal ou inférieur au niveau de l'emplacement de sort que vous utilisez.



### Éclair
```yml
title: "Éclair"
description: "Ligne de foudre de 30 mètres de long qui inflige 8d6 dégâts."
school: "Évocation"
level: 3
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "personnelle (ligne de 30 mètres)"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un peu de fourrure et une baguette en ambre, en cristal ou en verre"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Un éclair formant une ligne de 30 mètres de long pour 1,50 mètre de large jaillit de votre personne et file dans la direction de votre choix. Chaque créature située sur la ligne doit réaliser un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. Celles qui échouent subissent 8d6 dégâts de foudre, les autres la moitié seulement.

La foudre embrase les objets inflammables de la zone qui ne sont ni portés ni transportés par une créature.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, les dégâts augmentent de 1d6 par niveau au-delà du niveau 3.



### Forme gazeuse
```yml
title: "Forme gazeuse"
description: "Transforme une cible consentante en nuage brumeux."
school: "Transmutation"
level: 3
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 heure"
range: "contact"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un morceau de gaze et une volute de fumée"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Vous touchez une créature consentante et la transformez, ainsi que tous les objets qu'elle porte et qu'elle transporte, en nuage brumeux pour toute la durée du sort. Ce dernier se termine si la créature tombe à 0 point de vie. Le sort n'affecte pas les créatures intangibles.

Sous cette forme, la cible n'a plus qu'un seul mode de déplacement : le vol, à une vitesse de 3 mètres. Elle peut entrer dans l'espace d'une autre créature et l'occuper. Elle est résistante aux dégâts non magiques et elle bénéficie d'un [_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors des jets de sauvegarde de Force, de Dextérité et de Constitution. Elle peut passer à travers de petits trous, de minces ouvertures et même de simples fissures. En revanche, les liquides équivalent pour elle à des surfaces solides. Elle ne peut pas tomber et continue de flotter dans les airs même si elle est [_étourdie_](/gerer-la-sante-du-personnage/#etourdi) ou [_neutralisée_](/gerer-la-sante-du-personnage/#neutralise).

Sous forme de nuage brumeux, la cible ne peut pas parler ni manipuler d'objet. Il lui est impossible de lâcher les objets qu'elle portait et qu'elle transportait, et personne ne peut les utiliser ni interagir avec eux. Elle ne peut pas attaquer ni lancer de sort.



### Hâte
```yml
title: "Hâte"
description: "La cible double sa vitesse, a +2 à la CA, une action de plus par tour et d'autres bonus."
school: "Transmutation"
level: 3
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "9 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un copeau de racine de réglisse"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Choisissez une créature consentante située à portée et dans votre champ de vision. Jusqu'à la fin du sort, la cible voit sa vitesse doubler, bénéficie d'un bonus de +2 à la CA, a l'[_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors des jets de sauvegarde de Dextérité et dispose d'une action de plus par tour. Cette action est uniquement réservée aux actions suivantes : [_attaquer_](/combattre/#attaquer) (permet seulement une unique attaque), [_se précipiter_](/combattre/#se-precipiter), [_se désengager_](/combattre/#se-desengager), [_se cacher_](/combattre/#se-cacher) ou _utiliser un objet_.

Quand le sort se termine, la cible ne peut pas se déplacer ni effectuer une action avant que son prochain tour ne se soit écoulé, car une vague de léthargie déferle sur elle.





### Image majeure
```yml
title: "Image majeure"
description: "Illusion visuelle, auditive et sensorielle très fidèle qui peut être déplacée."
school: "Illusion"
level: 3
concentration: true
casting_time: "1 action"
duration: "jusqu'à 10 minutes"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un morceau de toison"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Vous créez l'image d'un objet, d'une créature ou d'un phénomène visible pas plus grand qu'un cube de 6 mètres d'arête. L'image apparaît en un point situé à portée et dans votre champ de vision et persiste pendant toute la durée du sort. Elle a l'air absolument réelle et s'accompagne des sons, des odeurs et de la température appropriés pour la chose qu'elle représente. En revanche, elle ne dégage pas assez de chaleur ou de froid pour blesser quelqu'un, ne génère pas de son assez puissant pour provoquer des dégâts de tonnerre pour qu'une créature soit [_assourdie_](/gerer-la-sante-du-personnage/#assourdi), et n'émet pas une odeur assez puissante pour écœurer une créature (comme le fait la puanteur du troglodyte).

Tant que vous êtes à portée de l'illusion, vous pouvez utiliser votre action pour déplacer l'image vers un autre point situé à portée. Quand l'image bouge, vous pouvez modifier son apparence de manière à ce que ses mouvements paraissent naturels. Par exemple, si vous créez l'image d'une créature et la déplacez, vous pouvez modifier l'image pour donner l'impression que la créature marche. De même, vous pouvez modifier les sons que l'image émet, à tel point que vous pouvez lui faire tenir une conversation, par exemple.

Les interactions physiques avec l'image révèlent qu'elle n'est qu'une illusion, car les objets la traversent. Si une créature utilise son action pour examiner l'image, elle comprend que c'est une illusion à condition de réussir un test d'Intelligence (Investigation) contre le DD du [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de votre sort. Si une créature perce l'illusion à jour, elle voit à travers l'image et ne perçoit plus que faiblement ses autres propriétés sensorielles.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, le sort persiste jusqu'à dissipation, sans que vous ayez besoin de vous concentrer.




### Langues
```yml
title: "Langues"
description: "La cible comprend et peut parler toutes les langues."
school: "Divination"
level: 3
concentration: false
casting_time: "1 action"
duration: "1 heure"
range: "contact"
components:
  verbal: true
  somatic: false
  material: true
  materials: "un modèle réduit de ziggourat en argile"
ritual: false
classes:
    - Barde
    - Clerc
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Ce sort permet à la créature que vous touchez de comprendre toutes les langues parlées qu'elle entend. De plus, quand elle parle, toute créature qui maîtrise au moins une langue et l'entend comprend ce qu'elle dit.




### Lenteur
```yml
title: "Lenteur"
description: "Les cibles voient leur vitesse, leur CA et leur nombre d'actions diminués."
school: "Transmutation"
level: 3
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une goutte de mélasse"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous modifiez le cours du temps autour d'un maximum de six créatures de votre choix situées dans un cube de 12 mètres d'arête situé à portée. Chaque cible doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse, sans quoi le sort l'affecte pendant toute sa durée.

Une cible affectée voit sa vitesse réduite de moitié. De plus, elle subit un malus de -2 à la CA et aux jets de sauvegarde de Dextérité et ne peut plus utiliser de réaction. À son tour, elle peut utiliser une action ou une action bonus, mais pas les deux. Elle ne peut pas faire plus d'une attaque au corps-à-corps ou à distance à son tour, quels que soient ses aptitudes et ses objets magiques.

Si la créature affectée tente de lancer un sort doté d'un temps d'incantation de 1 action, lancez 1d20. Sur un résultat de 11 ou plus, le sort agit seulement au prochain tour de la créature, qui doit utiliser son action de ce tour pour terminer l'incantation. Si elle en est incapable, le sort n'a aucun effet.

Une créature affectée par ce sort fait un nouveau [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse à la fin de chacun de ses tours. Si elle le réussit, le sort se termine pour elle.




### Lumière du jour
```yml
title: "Lumière du jour"
description: "Crée une sphère de lumière vive."
school: "Évocation"
level: 3
concentration: false
casting_time: "1 action"
duration: "1 heure"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Clerc
    - Druide
    - Ensorceleur/Sorcelame
    - Paladin
    - Rôdeur
```
Une sphère de lumière de 18 mètres de rayon s'étend depuis un point de votre choix situé à portée. Elle émet une lumière vive dans ce rayon et une lumière faible dans un rayon additionnel de 18 mètres.

Si le point que vous avez choisi est un objet en votre possession ou un objet qui n'est ni porté ni transporté par autrui, la lumière irradie de l'objet et se déplace avec lui. Il suffit de recouvrir complètement l'objet affecté avec un objet opaque, comme un bol ou un heaume, pour bloquer la lumière.

Si une partie de la zone affectée par ce sort chevauche une zone de ténèbres issue d'un sort de niveau 3 ou moins, elle dissipe le sort en question.




### Marche sur l'eau
```yml
title: "Marche sur l'eau"
description: "Les cibles marchent sur une surface liquide comme si elle était solide."
school: "Transmutation"
level: 3
concentration: false
casting_time: "1 action"
duration: "1 heure"
range: "9 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un bout de liège"
ritual: true
classes:
    - Clerc
    - Druide
    - Ensorceleur/Sorcelame
    - Rôdeur
```
Ce sort permet de se déplacer sur n'importe quelle surface liquide (comme de l'eau, de l'acide, de la boue, de la neige, des sables mouvants ou de la lave) comme s'il s'agissait d'un sol ferme et inoffensif (ceci dit, les créatures qui marchent sur la lave subissent tout de même les dégâts liés à la chaleur dégagée). Vous pouvez accorder cette capacité pendant toute la durée du sort à un maximum de dix créatures consentantes situées à portée et dans votre champ de vision.

Si vous prenez pour cible une créature immergée dans un liquide, le sort la ramène à la surface du liquide à une vitesse de 18 mètres par round.






### Motif hypnotique
```yml
title: "Motif hypnotique"
description: "Cibles <em>charmées</em> et <em>neutralisées</em> dans un cube de 9 mètres."
school: "Illusion"
level: 3
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "36 mètres"
components:
  verbal: false
  somatic: true
  material: true
  materials: "un bâtonnet d'encens incandescent ou une fiole de cristal remplie d'une matière phosphorescente"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Vous tissez dans les airs un motif aux couleurs mouvantes dans un cube de 9 mètres d'arête situé à portée. Le motif apparaît pendant un bref instant avant de s'évanouir. Chaque créature qui se trouve dans la zone et voit le motif doit faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse. Celles qui échouent sont charmées pendant la durée du sort. Tant qu'une créature est [_charmée_](/gerer-la-sante-du-personnage/#charme) par ce sort, elle est [_neutralisée_](/gerer-la-sante-du-personnage/#neutralise) et a une vitesse de 0.

Le sort se termine pour une créature donnée si elle subit le moindre dégât ou si quelqu'un d'autre utilise son action pour la secouer et la sortir de sa torpeur.





### Nuage puant
```yml
title: "Nuage puant"
description: "Nuage de gaz dans une sphère de 6 mètres qui cause des vomissements."
school: "Invocation"
level: 3
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "27 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un œuf pourri ou des feuilles de chou pourri"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
```
Vous créez une sphère d'un gaz jaunâtre et nauséabond de 6 mètres de rayon centrée sur un point à portée. Le nuage se répand en contournant les angles et la visibilité est nulle dans toute sa zone. Le nuage persiste dans la zone affectée pendant toute la durée du sort.

Chaque créature entièrement englobée dans le nuage au début de son tour doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution contre le poison. Celles qui échouent passent toutes leurs actions du tour à vomir. Les créatures qui ne respirent pas et celles qui sont immunisées contre le poison réussissent automatiquement ce jet.

Un vent modéré (au moins 15 km/h) disperse le nuage après 4 rounds. Un vent fort (au moins 30 km/h) le disperse au bout de seulement 1 round.





### Peur
```yml
title: "Peur"
description: "Dans un cône de 9 mètres les cibles sont <em>terrorisées</em> et fuient."
school: "Illusion"
level: 3
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "personnelle (cône de 9 mètres)"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une plume blanche ou un cœur de poule"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous projetez une image fantasmagorique des pires terreurs d'une créature. Chaque créature située dans un cône de 9 mètres doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse ou lâcher tout ce qu'elle tient en main et être [_terrorisée_](/gerer-la-sante-du-personnage/#terrorise) pendant toute la durée du sort.

Tant qu'une créature est [_terrorisée_](/gerer-la-sante-du-personnage/#terrorise) par ce sort, elle est obligée d'utiliser l'action se précipiter à chacun de ses tours et de s'éloigner de vous par l'itinéraire le plus sûr, à moins qu'elle n'ait nulle part où aller. Si elle termine son tour en un endroit où vous ne figurez plus dans son champ de vision, elle peut faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse. Si elle le réussit, le sort se termine pour elle.



### Protection contre les énergies
```yml
title: "Protection contre les énergies"
description: "La cible devient résistante aux dégâts d'un certain type."
school: "Abjuration"
level: 3
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 heure"
range: "contact"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Clerc
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Rôdeur
```
Pendant toute la durée du sort, la créature consentante que vous touchez devient résistante à un type de dégâts de votre choix : acide, feu, froid, foudre ou tonnerre.




### Respiration aquatique
```yml
title: "Respiration aquatique"
description: "Jusqu'à dix cibles peuvent respirer sous l'eau."
school: "Transmutation"
level: 3
concentration: false
casting_time: "1 action"
duration: "24 heures"
range: "9 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un petit roseau ou un brin de paille"
ritual: true
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Rôdeur
```
Grâce à ce sort, un maximum de dix créatures situées à portée et dans votre champ de vision deviennent capables de respirer sous l'eau jusqu'à la fin du sort. Les créatures affectées conservent en plus leur mode de respiration normal.





### Tempête de neige
```yml
title: "Tempête de neige"
description: "Invoque une tempête qui fait chuter les créatures."
school: "Invocation"
level: 3
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "45 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une pincée de poussière et quelques gouttes d'eau"
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
```
Jusqu'à la fin du sort, une averse de flocons et de neige fondue s'abat dans un cylindre de 6 mètres de haut pour un rayon de 12 mètres centré sur un point de votre choix situé à portée. Dans la zone, la visibilité est nulle et les flammes à nu s'éteignent.

Le sol de la zone est couvert d'une couche de verglas si glissante que le terrain devient difficile. Quand une créature entre dans la zone d'effet pour la première fois de son tour ou y débute son tour, elle doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité ou tomber [_à terre_](/gerer-la-sante-du-personnage/#a-terre).

Si une créature se concentre dans la zone d'effet du sort, elle doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution contre le DD du [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de votre sort, ou perdre sa concentration.




### Vol
```yml
title: "Vol"
description: "La cible obtient la capacité de voler à une vitesse de 18 mètres."
school: "Transmutation"
level: 3
concentration: true
casting_time: "1 action"
duration: "jusqu'à 10 minutes"
range: "contact"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une rémige"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous touchez une créature consentante et lui conférez la capacité de voler à une vitesse de 18 mètres pendant toute la durée du sort. Si la cible se trouve dans les airs quand le sort se termine, elle tombe, à moins de pouvoir arrêter sa chute.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, vous pouvez viser une créature de plus par niveau au-delà du niveau 3.





## Niveau 4

### Bannissement
```yml
title: "Bannissement"
description: "Envoie la cible dans un demi-plan ou dans son plan d'origine."
school: "Abjuration"
level: 4
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un objet qui répugne à la cible"
ritual: false
classes:
    - Clerc
    - Ensorceleur/Sorcelame
    - Magicien
    - Paladin
    - Sorcier
```
Vous tentez d'envoyer une créature située dans votre champ de vision dans un autre plan d'existence. Elle doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Charisme ou être bannie.

Si la cible est native du plan d'existence sur lequel vous vous trouvez, vous l'exilez dans un demi-plan inoffensif. Elle est [_neutralisée_](/gerer-la-sante-du-personnage/#neutralise) tant qu'elle se trouve là-bas et y reste jusqu'à la fin du sort. À ce moment, elle réapparaît à l'endroit qu'elle a quitté, ou dans l'emplacement inoccupé le plus proche si son emplacement de départ est occupé.

Si la cible est originaire d'un plan d'existence autre que celui sur lequel vous vous trouvez, une légère détonation accompagne son retour contraint sur son plan d'origine. Si le sort se termine avant que 1 minute ne se soit écoulée, la cible réapparaît à l'endroit qu'elle a quitté, ou dans l'emplacement inoccupé le plus proche si son emplacement de départ est occupé. Sinon, elle ne revient pas.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 5 ou supérieur, vous pouvez viser une créature de plus par niveau au-delà du niveau 4.




### Confusion
```yml
title: "Confusion"
description: "Les cibles agissent de manière aléatoire."
school: "Enchantement"
level: 4
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "27 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "trois coquilles de noix"
ritual: false
classes:
    - Barde
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
```
Ce sort assaille et pervertit l'esprit des créatures, génère des hallucinations et provoque des réactions incontrôlées. Toutes les créatures situées dans une sphère de 3 mètres de rayon autour d'un point de votre choix situé à portée doivent réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse ou être affectées par ce sort.

Une cible affectée ne peut pas utiliser de réaction et doit lancer 1d10 au début de chacun de ses tours pour déterminer comment elle se comporte pendant le tour.


|D10|Comportement|
|:-:|:-|
|**1**|La créature utilise la totalité de son mouvement pour se déplacer dans une direction aléatoire. Pour déterminer cette dernière, lancez un d8 en assignant une direction à chaque face. La créature n'effectue aucune action pour ce tour.|
|**2-6**|La créature ne bouge pas et n'entreprend pas la moindre action pour ce tour.|
|**7-8**|La créature utilise son action pour porter une attaque au corps-à-corps contre une créature aléatoire à portée d'allonge. S'il n'y a pas de créature à portée, elle ne fait rien durant le tour.|
|**9-10**|La créature peut agir et se déplacer normalement.|


Une créature affectée peut faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse à la fin de chacun de ses tours. En cas de succès, l'effet se termine pour elle.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 5 ou supérieur, le rayon de la sphère augmente de 1,50 mètre par niveau au-delà du niveau 4.





### Dominer une bête
```yml
title: "Dominer une bête"
description: "La bête ciblée est <em>charmée</em> et obéit au PJ."
school: "Enchantement"
level: 4
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
```
Vous tentez d'envoûter une bête située à portée et dans votre champ de vision. Elle doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse, sans quoi elle est [_charmée_](/gerer-la-sante-du-personnage/#charme) par vous pendant toute la durée du sort. Elle dispose d'un [_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors du [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) si vous ou des créatures amicales envers vous êtes en train de la combattre.

Tant que la bête est [_charmée_](/gerer-la-sante-du-personnage/#charme), vous entretenez un lien télépathique avec elle qui persiste tant que vous vous trouvez sur le même plan d'existence. Vous pouvez utiliser ce lien télépathique pour donner des ordres à cette créature tant que vous êtes conscient (ce qui ne vous demande pas d'action). Elle fait de son mieux pour vous obéir. Vous pouvez lui donner un ordre simple et générique, comme «  _attaque cette créature_  », «  _cours jusque là-bas_  » ou « _va chercher cet objet_ ». Si elle ne reçoit pas de nouvelle instruction de votre part une fois l'ordre exécuté, elle se contente de se défendre et de se préserver au mieux.

Vous pouvez utiliser votre action pour prendre le contrôle total de votre cible et la diriger de façon précise. Jusqu'à la fin de votre prochain tour, elle exécute seulement les actions que vous choisissez et ne fait rien que vous ne lui ayez autorisé. Pendant cette période, vous pouvez aussi lui faire exécuter une réaction, mais vous devez pour cela également dépenser votre propre réaction.

À chaque fois que la cible subit des dégâts, elle a droit à un nouveau [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse contre le sort. Si elle le réussit, le sort prend fin.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 5, la durée devient « _concentration, jusqu'à 10 minutes_ ». Si vous lancez ce sort en utilisant un emplacement de niveau 6, la durée devient « _concentration, jusqu'à 1 heure_ ». Si vous lancez ce sort en utilisant un emplacement de niveau 7, la durée devient « _concentration, jusqu'à 8 heures_ ».




### Flétrissement
```yml
title: "Flétrissement"
description: "Inflige 8d8 dégâts, le maximum aux créatures végétales."
school: "Nécromancie"
level: 4
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "9 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
L'énergie nécromantique inonde une créature de votre choix située à portée et dans votre champ de vision, et draine ses fluides corporels et sa vitalité. La cible doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution. Si elle échoue, elle reçoit 8d8 dégâts nécrotiques, la moitié seulement si elle réussit son jet. Ce sort n'a aucun effet sur les morts-vivants ou les créatures artificielles.

Si vous visez une créature végétale ou une plante magique, elle subit un [_désavantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors du [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) et le sort lui inflige le maximum de dégâts possible. Si vous visez une plante non magique qui n'est pas une créature, comme un arbre ou un buisson, elle n'a pas droit au moindre jet de sauvegarde, mais se flétrit et meurt.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 5 ou supérieur, les dégâts augmentent de 1d8 par niveau au-delà du niveau 4.




### Invisibilité supérieure
```yml
title: "Invisibilité supérieure"
description: "La cible est <em>invisible</em> pendant toute la durée du sort."
school: "Illusion"
level: 4
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "contact"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
```
Vous devenez [_invisible_](/gerer-la-sante-du-personnage/#invisible) jusqu'à ce que le sort se termine, ou vous pouvez accorder cet effet à une créature consentante que vous touchez. Tout ce que porte la cible devient [_invisible_](/gerer-la-sante-du-personnage/#invisible) tant que les objets restent sur sa personne.




### Métamorphose
```yml
title: "Métamorphose"
description: "Transforme la cible en bête au choix du PJ."
school: "Transmutation"
level: 4
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 heure"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un cocon de chenille"
ritual: false
classes:
    - Barde
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
```
Ce sort change la forme d'une créature située à portée et dans votre champ de vision. Une créature non consentante doit faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse pour éviter cet effet. Le sort n'a aucun effet sur un métamorphe ou une créature à 0 point de vie.

La transformation persiste pendant toute la durée du sort ou jusqu'à ce que la cible tombe à 0 point de vie ou meure. Vous pouvez donner comme nouvelle forme celle de n'importe quelle bête dont l'indice de dangerosité est égal ou inférieur à celui de la cible (ou à son niveau, si elle n'a pas d'indice de dangerosité). Le profil technique de la cible, y compris ses valeurs de caractéristique mentales, est remplacé par celui de la bête choisie. Elle conserve en revanche son alignement et sa personnalité.

La cible possède les points de vie correspondant à sa nouvelle forme. Quand elle reprend sa forme initiale, elle se retrouve avec le nombre de points de vie qui était le sien avant la transformation. Si elle reprend sa forme initiale parce qu'elle est tombée à 0 point de vie, les éventuels dégâts en excès sont déduits des points de vie de sa forme d'origine. Tant que les dégâts en excès ne réduisent pas les points de vie normaux de la créature à 0, elle n'est pas [_inconsciente_](/gerer-la-sante-du-personnage/#inconscient).

La nouvelle forme de la créature limite les actions qu'elle peut entreprendre et elle ne peut ni parler, ni lancer de sorts, ni effectuer une action qui nécessite de parler ou de se servir de ses mains.

L'équipement de la cible fusionne avec sa nouvelle forme, mais elle ne peut pas activer, utiliser ni manier la moindre pièce d'équipement et ne peut pas non plus bénéficier de ses effets.



### Mur de feu
```yml
title: "Mur de feu"
description: "Crée un mur qui inflige 5d8 dégâts aux créatures qui l'approchent."
school: "Évocation"
level: 4
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un éclat de phosphore"
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous créez un mur de feu sur une surface solide située à portée. Il peut faire un maximum de 18 mètres de long, 6 mètres de haut et 30 centimètres d'épaisseur, ou prendre une forme circulaire de 6 mètres de diamètre pour 6 mètres de haut et 30 centimètres d'épaisseur. Le mur est opaque et persiste toute la durée du sort.

Quand le mur apparaît, chaque créature présente dans sa zone d'effet doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. Celles qui échouent reçoivent 5d8 dégâts de feu, les autres la moitié seulement.

Une face du mur (celle de votre choix) inflige 5d8 dégâts de feu à chaque créature qui termine son tour à 3 mètres d'elle ou moins ou au sein du mur. Une créature qui pénètre dans le mur pour la première fois de son tour ou y termine son tour subit les mêmes dégâts. L'autre face du mur n'inflige pas de dégâts.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 5 ou supérieur, les dégâts augmentent de 1d8 par niveau au-delà du niveau 4.





### Peau de pierre
```yml
title: "Peau de pierre"
description: "La cible est résistante aux dégâts contondants, perforants et tranchants."
school: "Abjuration"
level: 4
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 heure"
range: "contact"
components:
  verbal: true
  somatic: true
  material: true
  materials: "poussière de diamant d'une valeur de 100 po, que le sort consume"
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
    - Rôdeur
```
Ce sort modifie la chair d'une créature consentante pour la rendre aussi dure que de la pierre. Jusqu'à la fin du sort, la cible est résistante aux dégâts non magiques contondants, perforants et tranchants.





### Porte dimensionnelle
```yml
title: "Porte dimensionnelle"
description: "Déplacement instantané jusqu'à 150 mètres."
school: "Invocation"
level: 4
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "150 mètres"
components:
  verbal: true
  somatic: false
  material: false
  materials: ""
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Ombrelame
    - Sorcier
```
Vous vous téléportez depuis votre position actuelle vers n'importe quel emplacement désiré situé à portée. Vous arrivez exactement à l'endroit voulu. Ce peut être un endroit que vous voyez, que vous visualisez ou que vous pouvez décrire en donnant sa distance et sa direction, par exemple « _60 mètres plus bas en ligne droite_ » ou « _en montant au nord-ouest à un angle de 45 degrés sur 90 mètres_ ».

Vous pouvez amener des objets avec vous, tant que leur poids ne dépasse pas la charge que vous êtes capable de porter. Vous pouvez également emmener avec vous une créature consentante de votre taille ou d'une taille inférieure, qui peut transporter du matériel dans la limite de ses capacités. Elle doit se trouver dans un rayon de 1,50 mètre autour de vous quand vous lancez le sort.

Si vous deviez arriver dans un emplacement déjà occupé par un objet ou une créature, vous et la créature qui voyage avec vous subissez chacun 4d6 dégâts de force tandis que le sort s'avère incapable de vous téléporter.




### Tempête de grêle
```yml
title: "Tempête de grêle"
description: "Invoque une tempête qui inflige des dégâts contondants et de froid."
school: "Évocation"
level: 4
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "90 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une pincée de poussière et quelques gouttes d'eau"
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
```
Des grêlons durs comme de la pierre s'abattent dans un cylindre de 6 mètres de rayon pour 12 mètres de haut, centré sur un point de votre choix à portée. Chaque créature présente dans le cylindre doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. Celles qui échouent subissent 2d8 dégâts contondants et 4d6 dégâts de froid tandis que les autres en subissent la moitié seulement.

Les grêlons transforment la zone en terrain difficile jusqu'à la fin de votre prochain tour.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 5 ou supérieur, les dégâts contondants augmentent de 1d8 par niveau au-delà du niveau 4.






## Niveau 5

### Animation des objets
```yml
title: "Animation des objets"
description: "Permet d'animer jusqu'à 10 objets et de les contrôler."
school: "Transmutation"
level: 5
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
```
Les objets prennent vie sur votre ordre. Choisissez jusqu'à dix objets non magiques à portée que personne ne porte ni ne transporte. Les cibles de taille M comptent comme deux objets, celles de taille G comme quatre et celles de taille TG comme huit. Vous ne pouvez pas animer d'objet de taille supérieure. Chaque cible s'anime et devient une créature placée sous votre contrôle jusqu'à la fin du sort, ou jusqu'à tomber à 0 point de vie.

Par une action bonus, vous pouvez donner un ordre mental à toute créature créée via ce sort qui se trouve au maximum à 150 mètres de vous (si vous en contrôlez plusieurs, vous pouvez donner un ordre à l'une d'elles, certaines d'entre elles ou toutes à la fois, à condition de donner le même ordre à toutes). À vous de décider quelles actions la créature va entreprendre et à quel endroit elle se déplace au cours du tour suivant, mais vous pouvez aussi lui donner un ordre plus générique, comme de garder une salle ou un couloir. En l'absence d'ordre, la créature se contente de se défendre contre les créatures hostiles. Une fois qu'elle a reçu un ordre, elle continue à le suivre jusqu'à ce qu'elle ait accompli sa tâche.

Un objet animé est une créature artificielle avec une CA, des points de vie, des attaques, une Force et une Dextérité déterminés par sa taille. Sa Constitution est de 10 tandis que son Intelligence et sa Sagesse sont de 3 et son Charisme de 1. Il a une vitesse de 9 mètres. S'il est dépourvu de patte ou d'appendice susceptible de lui permettre de se mouvoir, il gagne à la place la capacité de voler à une vitesse de 9 mètres et peut utiliser le vol stationnaire. Si l'objet est solidement attaché à une surface ou à un objet de plus grande taille, comme une chaîne vissée à un mur, sa vitesse est de 0. L'objet possède la vision aveugle dans un rayon de 9 mètres ; au-delà, il est aveugle. Quand l'objet animé tombe à 0 point de vie, il reprend sa forme initiale et tout dégât en surplus est infligé à celle-ci.

Si vous ordonnez à un objet animé d'attaquer, il a droit à une attaque au corps-à-corps unique contre une créature située dans un rayon de 1,50 mètre. Il porte une attaque avec un bonus d'attaque et des dégâts contondants déterminés en fonction de sa taille. Le MJ peut tout à fait décider qu'un objet animé inflige des dégâts perforants ou tranchants si sa forme le lui permet.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, vous pouvez animer deux objets supplémentaires par emplacement au-delà du niveau 5.

## Profil technique des objets animés

|Taille|PV|CA|Attaque|For|Dex|
|:-|:-:|:-:|:-:|:-:|:-:|
|**Très petite**|20|18|+8 pour toucher, 1d4+4 dégâts|4|18|
|**Petite**|25|16|+6 pour toucher, 1d8+2 dégâts|6|14|
|**Moyenne**|40|13|+5 pour toucher, 2d6+1 dégâts|10|12|
|**Grande**|50|10|+6 pour toucher, 2d10+2 dégâts|14|10|
|**Très grande**|80|10|+8 pour toucher, 2d12+4 dégâts|18|6|






### Apparence trompeuse
```yml
title: "Apparence trompeuse"
description: "Illusion permettant de déguiser plusieurs cibles."
school: "Illusion"
level: 5
concentration: false
casting_time: "1 action"
duration: "8 heures"
range: "9 mètres"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
```
Ce sort vous permet de modifier l'apparence d'autant de créatures que vous voulez, à condition qu'elles se trouvent à portée et dans votre champ de vision. Vous donnez à chacune d'entre elles une nouvelle apparence illusoire. Une cible non consentante peut faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Charisme. Si elle le réussit, le sort ne l'affecte pas.

Ce sort change l'apparence physique, mais aussi les vêtements, les armures, les armes et le reste de l'équipement. Vous pouvez faire croire que chaque créature affectée est plus petite ou plus grande de 30 centimètres maximum qu'en réalité, lui donner l'air grosse, maigre ou de corpulence normale. Vous ne pouvez pas changer le type de son corps, et vous devez choisir une forme possédant la même conformation qu'elle au niveau des membres. En dehors de cela, les détails de l'illusion sont laissés à votre imagination. Le sort persiste pendant toute sa durée ou jusqu'à ce que vous utilisiez une action pour le révoquer.

Les changements apportés par le sort ne résistent pas à un examen physique. Par exemple, si vous l'utilisez pour ajouter un chapeau à la tenue de la cible, les objets passent au travers et toute personne qui essaie de le toucher ne sentira que de l'air ou des cheveux et un crâne. Si vous utilisez le sort pour la faire paraître plus mince qu'en réalité, la main de quelqu'un qui tente de la toucher se heurtera à son corps alors que, visuellement, elle semble encore dans le vide.

Une créature peut utiliser son action pour examiner une cible et faire un test d'Intelligence (Investigation) contre le DD du [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) du sort. Si elle le réussit, elle comprend que la cible est déguisée.





### Cercle de téléportation
```yml
title: "Cercle de téléportation"
description: "Crée un portail vers une destination lointaine."
school: "Invocation"
level: 5
concentration: false
casting_time: "1 minute"
duration: "1 round"
range: "3 mètres"
components:
  verbal: true
  somatic: false
  material: true
  materials: "des craies et des encres rares contenant des extraits de pierres précieuses pour une valeur de 50 po, que le sort consume"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
```
Lorsque vous lancez ce sort, vous tracez un cercle de 3 mètres de diamètre au sol et y inscrivez des symboles qui relient l'endroit où vous vous trouvez actuellement à un cercle de téléportation permanent de votre choix dont vous connaissez la séquence de symboles et qui se trouve sur le même plan d'existence que vous. Un portail scintillant s'ouvre dans le cercle que vous avez tracé et reste ouvert jusqu'à la fin de votre prochain tour. Toute créature qui franchit ce portail apparaît instantanément dans un rayon de 1,50 mètre autour du cercle de destination ou dans l'espace inoccupé le plus proche si le reste est occupé.

Nombre de temples majeurs, de guildes et d'autres lieux d'importance possèdent des cercles de téléportation permanents tracés quelque part dans leur enceinte. Chacun de ces cercles utilise une séquence de symboles uniques : une série de runes magiques disposées selon un motif particulier. Lorsque vous apprenez à lancer ce sort, vous apprenez la séquence associée à deux destinations situées sur le plan matériel et déterminées par le MJ. Vous pouvez apprendre d'autres séquences de symboles au cours de vos aventures. Pour en mémoriser une, vous devez l'étudier pendant 1 minute.

Vous pouvez créer un cercle de téléportation permanent en lançant ce sort au même endroit tous les jours pendant un an. Vous n'avez pas besoin d'utiliser le cercle pour vous téléporter quand vous lancez ce sort pour cela.




### Cône de froid
```yml
title: "Cône de froid"
description: "Cône de 18 mètres dans lequel les cibles subissent 8d8 dégâts de froid."
school: "Évocation"
level: 5
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "personnelle (cône de 18 mètres)"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un petit cône de cristal ou de verre"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Une bouffée d'air froid jaillit de vos mains. Toutes les créatures présentes dans un cône de 18 mètres doivent effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution. Celles qui le ratent subissent 8d8 dégâts de froid, les autres la moitié seulement.

Une créature qui succombe suite à ce sort se transforme en statue de glace jusqu'à ce qu'elle fonde.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, les dégâts augmentent de 1d8 par niveau au-delà du niveau 5.




### Création
```yml
title: "Création"
description: "Crée des objets végétaux ou minéraux de manière temporaire."
school: "Illusion"
level: 5
concentration: false
casting_time: "1 minute"
duration: "spéciale"
range: "9 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un petit bout de matière de même type que l'objet que vous voulez créer"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous tirez des bribes de matière ombreuse du plan de l'ombre pour créer à portée des objets inertes en matière végétale : du tissu, de la corde, du bois ou des objets similaires. Ce sort permet aussi de créer des objets minéraux comme de la pierre, du cristal ou du métal. L'objet créé ne doit pas être plus grand qu'un cube de 1,50  mètre d'arête et doit impérativement être d'une forme et d'un matériau que vous avez déjà vus.

La durée du sort dépend du matériau choisi pour façonner l'objet. S'il est fait de plusieurs matières, c'est la durée la plus courte qui s'applique.

|Matériau|Durée|
|:-|:-:|
|**Matière végétale**|1 jour|
|**Pierre ou cristal**|12 heures|
|**Métaux précieux**|1 heure|
|**Gemmes**|10 minutes|
|**Adamantium ou mithral**|1 minute|

Si vous utilisez les matériaux créés via ce sort comme composantes matérielles pour un autre sort, ce dernier échoue.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, l'arête du cube augmente de 1,50 mètre par niveau au-delà du niveau 5.




### Dominer un humanoïde
```yml
title: "Dominer un humanoïde"
description: "La cible est <em>charmée</em>, le PJ contrôle ses actions."
school: "Enchantement"
level: 5
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous tentez d'envoûter un humanoïde situé à portée et dans votre champ de vision. Il doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse, sans quoi il est [_charmé_](/gerer-la-sante-du-personnage/#charme) par vous pendant toute la durée du sort. Il dispose d'un [_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors du [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) si vous ou des créatures amicales envers vous êtes en train de le combattre.

Tant que l'humanoïde est [_charmé_](/gerer-la-sante-du-personnage/#charme), vous entretenez un lien télépathique avec lui qui persiste tant que vous vous trouvez sur le même plan d'existence. Vous pouvez utiliser ce lien télépathique pour donner des ordres à cette créature tant que vous êtes conscient (ce qui ne vous demande pas d'action). Elle fait de son mieux pour vous obéir. Vous pouvez lui donner un ordre simple et générique, comme «  _attaque cette créature_  », «  _cours jusque là-bas_  » ou «  _va chercher cet objet_  ». Si elle ne reçoit pas de nouvelle instruction de votre part une fois l'ordre exécuté, elle se contente de se défendre et de se préserver au mieux.

Vous pouvez utiliser votre action pour prendre le contrôle total de votre cible et la diriger de façon précise. Jusqu'à la fin de votre prochain tour, elle exécute seulement les actions que vous choisissez et ne fait rien que vous ne lui ayez autorisé. Pendant cette période, vous pouvez aussi lui faire exécuter une réaction, mais vous devez pour cela également dépenser votre propre réaction.

À chaque fois que la cible subit des dégâts, elle a droit à un nouveau [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse contre le sort. Si elle le réussit, le sort prend fin.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 6, la durée devient « _concentration, jusqu'à 10 minutes_ ». Si vous lancez ce sort en utilisant un emplacement de niveau 7, la durée devient « _concentration, jusqu'à 1 heure_  ». Si vous lancez ce sort en utilisant un emplacement de niveau 8, la durée devient « _concentration, jusqu'à 8 heures_ ».






### Fléau d'insectes
```yml
title: "Fléau d'insectes"
description: "Invoque des insectes qui attaquent et infligent 4d10 dégâts perforants."
school: "Invocation"
level: 5
concentration: true
casting_time: "1 action"
duration: "jusqu'à 10 minutes"
range: "90 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un peu de sucre en poudre, quelques graines de céréales et une tache de graisse"
ritual: false
classes:
    - Clerc
    - Druide
    - Ensorceleur/Sorcelame
```
Un essaim de sauterelles carnivores forme une sphère de 6 mètres de rayon centrée sur un point de votre choix situé à portée. La sphère s'étend en contournant les angles et persiste pendant toute la durée du sort. La visibilité est réduite dans la zone affectée. L'intérieur de la sphère devient un terrain difficile.

Quand la sphère d'insectes apparaît, chaque créature prise à l'intérieur doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution. Une créature subit 4d10 dégâts perforants si elle rate son jet, la moitié seulement si elle le réussit. Une créature doit effectuer le même jet quand elle entre dans la sphère pour la première fois de son tour ou quand elle y termine son tour.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, les dégâts augmentent de 1d10 par niveau au-delà du niveau 5.







### Immobiliser un monstre
```yml
title: "Immobiliser un monstre"
description: "La cible est <em>paralysée</em>."
school: "Enchantement"
level: 5
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "27 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un petit morceau de fer bien droit"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Choisissez une créature située à portée et dans votre champ de vision. Elle doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse, sans quoi elle est [_paralysée_](/gerer-la-sante-du-personnage/#paralyse) pour toute la durée du sort. Ce sort est sans effet sur les morts-vivants. À la fin de chacun de ses tours, la cible a droit à un nouveau [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse. Si elle le réussit, le sort se termine.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, vous pouvez viser une créature de plus par niveau au-delà du niveau 5. Les créatures visées doivent se trouver à 9 mètres ou moins les unes des autres au moment où vous lancez le sort.




### Mur de pierre
```yml
title: "Mur de pierre"
description: "Crée un mur de pierre qui peut devenir permanent."
school: "Évocation"
level: 5
concentration: true
casting_time: "1 action"
duration: "jusqu'à 10 minutes"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un petit bloc de granite"
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous créez un mur de pierre non magique qui se matérialise en un point de votre choix à portée. Il fait 15 centimètres d'épaisseur et se compose de dix panneaux de 3 mètres sur 3. Chaque panneau doit être contigu à un autre. Sinon, vous pouvez opter pour des panneaux de 3 mètres sur 6 de seulement 7,5 centimètres d'épaisseur.

Si le mur passe par l'emplacement d'une créature lorsqu'il apparaît, il l'expulse d'un côté ou de l'autre (à vous de choisir). Si une créature est placée de telle manière qu'elle devrait se retrouver entourée de toutes parts par le mur (ou par le mur et une autre surface solide), elle doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. Si elle le réussit, elle peut utiliser sa réaction pour se déplacer à sa vitesse au maximum afin de ne plus être encerclée par le mur.

Le mur peut prendre la forme que vous désirez, mais il ne peut pas occuper le même emplacement qu'une créature ou un objet. Il n'est pas forcément vertical et n'a pas besoin de reposer sur des fondations solides. En revanche, il doit impérativement fusionner avec de la pierre existante lui servant de soutien solide. Vous pouvez donc utiliser ce sort pour jeter un pont au-dessus d'un fossé ou créer une rampe.

Si vous créez une longueur de plus de 6 mètres, vous devez réduire de moitié la taille de chaque panneau pour créer des supports. Vous pouvez façonner la silhouette générale du mur pour le doter de créneaux, de remparts et autres.

Le mur est un objet de pierre que l'on peut endommager et on peut donc y ouvrir des brèches. Chaque panneau a une CA de 15 et 30 points de vie par section de 2,5 centimètres d'épaisseur. Si un panneau tombe à 0 point de vie, il est détruit, ce qui peut entraîner l'effondrement des panneaux adjacents, au choix du MJ.

Si vous restez concentré sur le sort pendant toute sa durée, le mur devient une structure permanente et ne peut plus être dissipé, sinon il disparaît à la fin du sort.





### Nuage mortel
```yml
title: "Nuage mortel"
description: "Les créatures qui respirent le brouillard subissent 5d8 dégâts de poison."
school: "Invocation"
level: 5
concentration: true
casting_time: "1 action"
duration: "jusqu'à 10 minutes"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous créez une sphère de 6 mètres de rayon faite d'un brouillard verdâtre toxique. Il est centré sur un point de votre choix situé à portée. Le brouillard s'étend en contournant les coins au besoin. Il persiste pendant toute la durée du sort ou jusqu'à ce qu'un vent fort le disperse et mette un terme au sort. La visibilité est nulle dans sa zone d'effet.

Quand une créature entre dans la zone du sort pour la première fois de son tour ou qu'elle y débute son tour, elle doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution. Elle subit 5d8 dégâts de poison si elle rate son jet et seulement la moitié si elle le réussit. Le brouillard affecte même les créatures qui retiennent leur souffle ou qui n'ont pas besoin de respirer.

Le brouillard s'éloigne de vous sur une distance de 3  mètres au début de chacun de vos tours, rampant à la surface du sol. Comme ses vapeurs sont plus lourdes que l'air, il s'enfonce dans les replis du terrain et s'infiltre même dans les ouvertures.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, les dégâts augmentent de 1d8 par niveau au-delà du niveau 5.




### Télékinésie
```yml
title: "Télékinésie"
description: "Le PJ peut déplacer des créatures ou des objets à distance."
school: "Transmutation"
level: 5
concentration: true
casting_time: "1 action"
duration: "jusqu'à 10 minutes"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous devenez capable de déplacer ou de manipuler des créatures ou des objets par la pensée. Lorsque vous lancez ce sort, puis en tant qu'action à chaque round pendant toute la durée du sort, vous pouvez exercer votre force de volonté sur une créature ou un objet situés à portée et dans votre champ de vision, ce qui provoque l'effet approprié indiqué plus bas. Vous pouvez affecter la même cible, round après round, ou en choisir une nouvelle quand vous le désirez. Si vous changez de cible, la précédente n'est plus affectée.

**Créatures**. Vous pouvez essayer de déplacer une créature de taille TG ou inférieure. Faites un [test de caractéristique](/utiliser-les-caracteristiques/#tests-de-caracteristique) avec votre caractéristique d'incantation, opposé à un test de Force de la cible. Si vous l'emportez, vous déplacez la créature d'un maximum de 9 mètres dans la direction de votre choix, y compris en hauteur, mais pas hors de portée du sort. Jusqu'à la fin de votre prochain tour, la créature est entravée dans votre étreinte télékinétique. Une créature soulevée dans les airs reste suspendue dans le vide.

Lors des rounds suivants, vous pouvez utiliser votre action pour maintenir votre prise télékinétique sur la cible en répétant les tests opposés.

**Objets**. Vous pouvez essayer de déplacer un objet pesant au maximum 500 kilogrammes. Si cet objet n'est ni porté ni transporté, vous le déplacez automatiquement d'un maximum de 9 mètres dans la direction de votre choix, mais pas hors de portée du sort.

Si l'objet est porté ou transporté par une créature, faites un [test de caractéristique](/utiliser-les-caracteristiques/#tests-de-caracteristique) avec votre caractéristique d'incantation, opposé à un test de Force de cette créature. Si vous l'emportez, vous éloignez l'objet de cette créature sur un maximum de 9 mètres dans la direction de votre choix, mais pas hors de portée du sort.

Vous exercez un contrôle précis sur les objets pris dans votre étreinte télékinétique, vous pouvez donc manipuler un outil basique, ouvrir une porte ou un récipient, déposer un objet dans un récipient ou en retirer un, ou encore verser le contenu d'une fiole.




## Niveau 6

### Cercle de mort
```yml
title: "Cercle de mort"
description: "Les créatures dans la sphère subissent 8d6  dégâts nécrotiques."
school: "Nécromancie"
level: 6
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "45 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "la poudre d'une perle noire broyée d'une valeur minimale de 500 po"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Une sphère d'énergie négative s'étend dans un rayon de 18 mètres à partir d'un point situé à portée. Chaque créature située dans la sphère doit faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution. Celles qui échouent subissent 8d6 dégâts nécrotiques, les autres la moitié seulement.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, les dégâts augmentent de 2d6 par niveau au-delà du niveau 6.




### Chaîne d'éclairs
```yml
title: "Chaîne d'éclairs"
description: "Un éclair rebondit sur trois autres cibles qui subissent 10d8 dégâts."
school: "Évocation"
level: 6
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "450 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un éclat d'ambre, de verre ou de cristal, trois épingles en argent et un morceau de fourrure"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous créez un arc électrique qui file vers une cible de votre choix, située à portée et dans votre champ de vision. Trois éclairs bondissent ensuite de cette cible sur un maximum de trois autres cibles qui doivent toutes se trouver dans un rayon de 9 mètres autour de la première. Une cible peut être une créature ou un objet et ne peut recevoir qu'un seul éclair.

Chaque cible doit faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité et subit 10d8 dégâts de foudre en cas d'échec, la moitié en cas de réussite.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, un éclair de plus rebondit de la première cible vers une autre pour chaque niveau au-delà du niveau 6.





### Déplacer la terre
```yml
title: "Déplacer la terre"
description: "Modifie la forme de la terre dans un carré de 12 mètres de côté."
school: "Transmutation"
level: 6
concentration: true
casting_time: "1 action"
duration: "jusqu'à 2 heures"
range: "36 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une lame de fer et un petit sac contenant un mélange de terres : de l'argile, du terreau et du sable"
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
```
Choisissez une zone de terrain à portée d'au maximum 12 mètres de côté. Vous pouvez remodeler la terre, le sable ou l'argile qu'elle comporte comme bon vous semble pendant toute la durée du sort. Vous pouvez augmenter ou diminuer l'altitude de la zone, creuser ou combler une tranchée, ériger ou abattre un mur, ou former un pilier. L'amplitude de ces modifications ne peut pas excéder la moitié de la dimension la plus importante de la zone affectée. Donc, si vous modifiez une zone de 12 mètres de côté, vous pouvez créer un pilier de 6 mètres de haut au maximum, modifier l'altitude de la zone de 6 mètres au plus, creuser une tranchée d'un maximum de 6 mètres de profondeur, etc. Il faut 10 minutes pour finaliser ces modifications.

Au bout de chaque période de 10 minutes passées à vous concentrer sur le sort, vous pouvez choisir une nouvelle zone de terrain à modifier. Comme les transformations se produisent lentement, il est bien rare qu'une créature se retrouve piégée ou blessée à cause des mouvements du terrain.

Ce sort est incapable de manipuler la pierre naturelle et les constructions de pierre. La roche et les structures s'adaptent au nouvel agencement du terrain. Si vos modifications déstabilisent une structure, elle peut très bien s'effondrer.

De même, le sort n'affecte pas directement la croissance des plantes. La terre déplacée emporte les végétaux avec elle.




### Désintégration
```yml
title: "Désintégration"
description: "Rayon qui inflige 10d6+40 dégâts et peut désintégrer sa cible."
school: "Transmutation"
level: 6
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "de la magnétite et une pincée de poussière"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Un mince rayon de lumière verte jaillit de votre doigt pointé vers une cible située dans votre champ de vision et à portée. La cible peut être une créature, un objet ou une création de force magique, comme une barrière issue d'un <ST s="mur-de-force"/>.

Une créature visée par ce sort doit faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. Si elle le rate, elle subit 10d6+40 dégâts de force. Si ces dégâts la réduisent à 0 point de vie, elle est désintégrée.

Une créature désintégrée est réduite à l'état de fine poussière grise, tout comme tous les objets qu'elle porte et transporte, à l'exception des objets magiques. Pour ressusciter une créature ainsi désintégrée, il faut impérativement recourir à une <ST s="resurrection-supreme"/> ou un <ST s="souhait"/>.

Ce sort désintègre automatiquement les objets non magiques de taille G ou inférieure et les créations magiques de force. Si la cible est un objet de taille TG ou supérieure, le sort désintègre un cube de 3 mètres d'arête au sein de l'objet. Ce sort reste sans effet sur les objets magiques.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, les dégâts augmentent de 3d6 par niveau au-delà du niveau 6.





### Globe d'invulnérabilité
```yml
title: "Globe d'invulnérabilité"
description: "Barrière qui empêche les sorts de niveau 5 ou moins de la traverser."
school: "Abjuration"
level: 6
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "personnelle (3 mètres)"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une perle de verre ou de cristal qui explose à la fin du sort"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Une barrière immobile scintille légèrement dans un rayon de 3 mètres autour de vous et persiste pendant toute la durée du sort.

Tout sort de niveau 5 ou inférieur lancé depuis l'extérieur de la barrière se trouve dans l'incapacité d'affecter les créatures et les objets se trouvant à l'intérieur, même si le lanceur de sort utilise un emplacement de niveau supérieur. Le sort peut très bien viser les créatures et les objets situés au sein de la barrière, mais il n'a aucun effet sur eux. De même, la zone protégée par la barrière est exclue de la zone affectée par les sorts de ces niveaux.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, la barrière bloque les sorts d'un niveau de plus par niveau au-delà du niveau 6.






### Mauvais œil
```yml
title: "Mauvais œil"
description: "Le regard du PJ cause des effets néfastes pendant la durée du sort."
school: "Nécromancie"
level: 6
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "personnelle"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Pendant la durée du sort, vos yeux deviennent deux trous noirs regorgeant d'un pouvoir terrifiant. Une créature de votre choix, située dans votre champ de vision et dans un rayon de 18 mètres doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse ou se voir affectée par l'un des effets suivants, choisi par vos soins, pendant toute la durée du sort. À chacun de vos tours jusqu'à ce que le sort se termine, vous pouvez utiliser votre action pour viser une autre créature, mais vous ne pouvez pas reprendre pour cible une créature ayant déjà réussi un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) contre l'incantation de mauvais œil en cours.

**Nauséeux**. La cible est affectée par un [_désavantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors des jets d'attaque et des [tests de caractéristique](/utiliser-les-caracteristiques/#tests-de-caracteristique). Elle a droit à un nouveau [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse à la fin de chacun de ses tours. L'effet se termine si elle le réussit.

**Endormi**. La cible tombe [_inconsciente_](/gerer-la-sante-du-personnage/#inconscient). Elle se réveille si elle subit le moindre dégât ou si une tierce personne utilise une action pour la réveiller en la secouant.

**Paniqué**. Vous terrorisez la cible. À chacun de ses tours, la cible [_terrorisée_](/gerer-la-sante-du-personnage/#terrorise) doit utiliser l'action se précipiter et s'éloigner de vous via l'itinéraire le plus rapide et le plus sûr, à moins qu'elle n'ait nulle part où aller. Cet effet se termine si la cible gagne un emplacement situé à au moins 18 mètres de vous et d'où elle ne vous voit plus.




### Passage dimensionnel
```yml
title: "Passage dimensionnel"
description: "Forme un passage permettant la téléportation à 150 mètres."
school: "Invocation"
level: 6
concentration: true
casting_time: "1 action"
duration: "jusqu'à 10 minutes"
range: "150 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous désignez un point sur une surface à portée dans votre champ de vision et créez une ouverture circulaire de 1,50 mètre de diamètre entourée de runes rayonnantes. Avant la fin du sort, par une action bonus, vous désignez un deuxième point sur une autre surface située à 150 mètres ou moins de la première pour créer une seconde ouverture faisant le lien avec la première et formant un passage extra-dimensionnelle bidirectionnel. Les surfaces ne doivent pas forcément avoir la même inclinaison mais doivent être planes et solides (ex: sol, mur ou plafond) et ne pas comporter de métal.

Toute créature ou objet solide entrant par une ouverture ressort instantanément par l'autre, perpendiculairement à l'ouverture et en conservant sa vitesse. Il est ainsi possible de lancer un objet ou de tirer un projectile par l'ouverture, de ramasser un objet de l'autre côté, de laisser tomber un objet lourd par une ouverture dans le sol pour qu'il retombe de l'autre côté, de sauter au travers pour accéder de l'autre côté sur un passage en hauteur, etc.

Les ouvertures ne laissent pas passer les matières liquides ou gazeuses sauf si elles sont contenues (des flots d'eau ou de lave ne peuvent pas passer au travers, mais une bouteille, une fiole ou un seau d'eau oui). Les sorts et les énergies ne peuvent pas franchir le passage, toutefois la lumière non magique passe au travers ce qui permet de voir de l'autre côté. Si la surface désignée ne peut accueillir l'ouverture, le sort est perdu ou s'arrête. Chacune des ouvertures n'a pas d'épaisseur et n'a qu'une seule face correspondant avec l'autre.

**À plus haut niveau**. Lorsque vous lancez ce sort en utilisant un emplacement de sort de niveau 7 ou supérieur, le diamètre de l'ouverture augmente de 1,50 mètre par niveau au-delà du niveau 6.






### Rayon de soleil
```yml
title: "Rayon de soleil"
description: "Le PJ lance des rayons de lumière qui infligent 6d8 dégâts et <em>aveuglent</em>."
school: "Évocation"
level: 6
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "personnelle (ligne de 18 mètres)"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une loupe"
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
```
Un rayon de vive lumière jaillit de votre main sur une ligne de 18 mètres de long pour 1,50 mètre de large. Chaque créature située sur cette ligne doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution. Celles qui échouent subissent 6d8 dégâts radiants et sont <RT l="aveuglées" t="aveugle"/> jusqu'à la fin de votre prochain tour. Les autres subissent seulement la moitié des dégâts et ne sont pas <RT l="aveuglées" t="aveugle"/>. Les vases et les morts-vivants sont affectés par un [_désavantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors de ce [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde).

Vous pouvez créer une nouvelle ligne de lumière en dépensant votre action à n'importe quel tour jusqu'à la fin du sort.

Pendant toute la durée du sort, une boule de lumière brille dans votre main. Elle émet une lumière vive dans un rayon de 9 mètres et une lumière faible dans un rayon de 9 mètres supplémentaires. Cette lumière est de la même nature que la lumière du soleil.





### Suggestion de groupe
```yml
title: "Suggestion de groupe"
description: "Les cibles suivent les ordres du PJ pendant 24 heures."
school: "Enchantement"
level: 6
concentration: false
casting_time: "1 action"
duration: "24 heures"
range: "18 mètres"
components:
  verbal: true
  somatic: false
  material: true
  materials: "une langue de serpent et soit un rayon de miel, soit une goutte d'huile d'olive"
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous visez un maximum de douze créatures de votre choix, situées à portée et dans votre champ de vision et à même de vous entendre et de vous comprendre. Vous les influencez par magie de façon à ce qu'elles suivent la conduite que vous leur proposez (en seulement une phrase ou deux). Les créatures qui ne peuvent être _charmées_ sont immunisées contre ce sort. Vous devez formuler votre suggestion de manière à ce que la conduite à tenir semble tout à fait raisonnable. Si vous demandez à une créature de se poignarder, de se laisser tomber sur une lance, de s'immoler ou d'accomplir n'importe quelle action à l'évidence néfaste, l'effet du sort s'annule automatiquement.

Chaque cible doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse, sans quoi elle fait de son mieux pour suivre la conduite que vous lui avez suggérée et cela peut occuper toute la durée du sort. Si l'action suggérée peut se finir plus rapidement, le sort se termine quand la cible a accompli ce que vous lui aviez demandé.

Vous pouvez spécifier des conditions qui déclenchent une conduite spéciale pendant la durée du sort. Par exemple, vous pouvez suggérer à un groupe de soldats de donner tout leur argent au premier mendiant qu'ils rencontrent. Si les conditions ne sont pas remplies avant la fin du sort, la cible n'accomplit pas l'action.

Si vous (ou l'un de vos compagnons) blessez une créature affectée par ce sort, le sort se termine pour elle.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, la durée du sort est de 10 jours. Si vous utilisez un emplacement de niveau 8, elle est de 30 jours et si vous utilisez un emplacement de niveau 9, elle est de 1 an et 1 jour.





### Vision suprême
```yml
title: "Vision suprême"
description: "La cible repère les portes cachées par magie et voit le plan éthéré."
school: "Divination"
level: 6
concentration: false
casting_time: "1 action"
duration: "1 heure"
range: "contact"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un collyre coûtant 25 po, fait de poudre de champignon, de safran et de graisse, que le sort consume"
ritual: false
classes:
    - Barde
    - Clerc
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Grâce à ce sort, la créature consentante que vous touchez est capable de voir les choses telles qu'elles sont réellement. Pendant toute la durée du sort, la cible bénéficie de vision parfaite, repère les portes dérobées cachées par magie et voit le plan éthéré, tout cela dans un rayon de 36 mètres.




## Niveau 7

### Boule de feu à explosion retardée
```yml
title: "Boule de feu à explosion retardée"
description: "Explosion qui inflige au moins 12d6 dégâts de feu."
school: "Évocation"
level: 7
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "45 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une petite boule de guano de chauve-souris et du soufre"
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Un rayon de lumière jaune jaillit de votre doigt tendu et se condense pour former une bille luisante en un point de votre choix situé à portée pendant toute la durée du sort. Quand le sort se termine, soit parce que votre concentration se brise, soit parce que vous y mettez volontairement un terme, la bille se dilate dans un grondement sourd et explose en une gerbe de feu qui s'étend en franchissant les angles éventuels. Toutes les créatures situées dans une sphère de 6 mètres de rayon centrée sur le point où se trouvait la bille doivent faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. Celles qui échouent subissent un montant de dégâts de feu égal au total de dégâts accumulés (voir plus loin), les autres la moitié seulement.

À la base, le sort inflige 12d6 dégâts de feu. À la fin de votre tour, si la bille n'a pas encore explosé, ces dégâts augmentent de 1d6.

Si quelqu'un touche la bille avant la fin de l'intervalle, il doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. S'il échoue, le sort se termine immédiatement et la bille explose. S'il réussit, il peut lancer la bille à une distance maximale de 12 mètres. Si elle touche un objet solide ou une créature, le sort se termine et la bille explose.

Les flammes endommagent les objets qui se trouvent dans la zone et embrasent les objets inflammables qui ne sont ni portés ni transportés.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 8 ou supérieur, les dégâts de base augmentent de 1d6 par niveau au-delà du niveau 7.



### Changement de plan
```yml
title: "Changement de plan"
description: "Transporte le PJ et huit alliés sur un autre plan d'existence."
school: "Invocation"
level: 7
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "contact"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un diapason de métal valant au moins 250 po, harmonisé avec un plan d'existence donné"
ritual: false
classes:
    - Clerc
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous et un maximum de huit autres créatures consentantes vous donnez la main pour former un cercle, et êtes transportés sur un autre plan d'existence. Vous pouvez spécifier une destination en termes génériques, comme le nom d'une cité, d'une région ou d'un endroit spécifique dans l'un des plans. Vous apparaissez alors à cet endroit ou à proximité. C'est au MJ de décider l'endroit exact de votre arrivée.

Sinon, si vous connaissez la séquence de glyphes magiques d'un cercle de téléportation présent sur un autre plan d'existence, ce sort peut vous conduire dans ce cercle. S'il est trop étroit pour accueillir toutes les créatures qui voyagent avec vous, les créatures en trop apparaissent dans les emplacements inoccupés les plus proches du cercle.

Vous pouvez aussi utiliser ce sort pour bannir une créature non consentante sur un autre plan. Choisissez une créature à votre portée et faites une attaque de sort au corps-à-corps contre elle. Si vous touchez, elle doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Charisme ou être transporté en un endroit aléatoire du plan d'existence que vous nommez. Une fois à cet endroit, c'est à elle de trouver un moyen de rentrer sur son plan d'origine.



### Doigt de mort
```yml
title: "Doigt de mort"
description: "Rayon qui inflige 7d8+30 dégâts et peut transformer la cible en zombi."
school: "Nécromancie"
level: 7
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous envoyez de l'énergie négative dans le corps d'une créature située à portée et dans votre champ de vision, ce qui lui inflige des douleurs déchirantes. La cible doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution. Si elle échoue, elle subit 7d8+30 dégâts nécrotiques, la moitié seulement si elle réussit.

Si ce sort achève un humanoïde, ce dernier se relève au début de votre prochain tour sous forme de zombi à jamais sous votre contrôle. Il suit vos ordres verbaux au mieux de ses capacités.



### Embruns prismatiques
```yml
title: "Embruns prismatiques"
description: "Huit rayons aux effets aléatoires frappent les cibles à 18 mètres."
school: "Évocation"
level: 7
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "personnelle (cône de 18 mètres)"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Huit rayons de lumière multicolores jaillissent de votre main. Chacun a une couleur différente et possède des pouvoirs et objectifs distincts. Chaque créature présente dans un cône de 18 mètres doit faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. Lancez 1d8 par cible pour savoir quelle couleur l'affecte.

1. **_Rouge_**. La cible subit 10d6 dégâts de feu si elle rate son jet de sauvegarde, la moitié seulement si elle le réussit.
2. **_Orange_**. La cible subit 10d6 dégâts d'acide si elle rate son jet de sauvegarde, la moitié seulement si elle le réussit.
3. **_Jaune_**. La cible subit 10d6 dégâts de foudre si elle rate son jet de sauvegarde, la moitié seulement si elle le réussit.
4. **_Vert_**. La cible subit 10d6 dégâts de poison si elle rate son jet de sauvegarde, la moitié seulement si elle le réussit.
5. **_Bleu_**. La cible subit 10d6 dégâts de froid si elle rate son jet de sauvegarde, la moitié seulement si elle le réussit.
6. **_Indigo_**. Si la cible rate son jet de sauvegarde, elle est entravée et doit alors faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution à la fin de chacun de ses tours. Si elle en réussit trois, le sort se termine, si elle en rate trois, elle se change définitivement en pierre et est pétrifiée. Les succès et les échecs n'ont pas à être consécutifs : tenez le compte dans chaque catégorie jusqu'à ce que l'une d'elles arrive à trois.
7. **_Violet_**. La cible est aveuglée si elle rate son [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde). Elle doit alors faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse au début de votre prochain tour. Si elle le réussit, elle recouvre la vue ; si elle le rate, elle est emportée sur un autre plan d'existence choisi par le MJ et recouvre aussi la vue. (En général, une créature qui ne se trouve pas sur son propre plan d'existence est bannie là-bas tandis que les autres créatures sont envoyées sur le plan astral ou éthéré.)
8. **_Spécial_**. Deux rayons viennent frapper la cible. Relancez deux fois le dé en le relançant à chaque fois que vous obtenez un 8.




### Forme éthérée
```yml
title: "Forme éthérée"
description: "Le PJ entre sur le plan éthéré et peut s'y déplacer."
school: "Transmutation"
level: 7
concentration: false
casting_time: "1 action"
duration: "jusqu'à 8 heures"
range: "personnelle"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Barde
    - Clerc
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous pénétrez dans la région frontalière du plan éthéré, dans une zone où il chevauche votre plan actuel. Vous restez sur la frontière éthérée pendant toute la durée du sort ou jusqu'à ce que vous utilisiez une action pour y mettre fin. Pendant cette période, vous pouvez vous déplacer dans n'importe quelle direction. Si vous optez pour un déplacement vers le haut ou le bas, le prix du mouvement est doublé, chaque mètre de déplacement vous coûtant 1 mètre supplémentaire. Vous voyez et entendez ce qui se passe sur le plan d'où vous venez, mais tout y est gris et vous ne voyez plus rien au-delà de 18 mètres.

Une fois sur le plan éthéré, vous pouvez affecter uniquement des créatures situées sur ce plan, et elles sont les seules à pouvoir vous affecter. Celles qui ne se trouvent pas sur ce plan ne vous perçoivent pas et sont incapables d'interagir avec vous, à moins qu'un pouvoir spécial ou magique ne le leur permette.

Les objets et effets qui ne se trouvent pas sur le plan éthéré n'ont aucune incidence sur vous, ce qui vous permet de traverser des objets que vous apercevez sur le plan d'où vous venez.

Quand le sort se termine, vous retournez immédiatement sur le plan d'où vous venez, à l'endroit que vous occupez actuellement. Si vous occupez le même emplacement qu'un objet solide ou une créature lorsque cela se produit, vous êtes immédiatement projeté dans l'espace inoccupé le plus proche susceptible de vous accueillir et subissez 6 points de dégâts de force par mètre de distance de cette projection.

Ce sort n'a aucun effet si vous le lancez alors que vous vous trouvez sur le plan éthéré ou sur un plan non limitrophe, comme les plans extérieurs.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 8 ou supérieur, vous pouvez affecter jusqu'à trois créatures consentantes (vous y compris) par niveau au-delà du niveau 7. Toutes ces créatures doivent se trouver dans un rayon de 3 mètres autour de vous quand vous lancez le sort.



### Inversion de la gravité
```yml
title: "Inversion de la gravité"
description: "Inverse la gravité dans un cylindre de 15 mètres sur 30."
school: "Transmutation"
level: 7
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "30 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "de la magnétite et de la limaille de fer"
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
```
Ce sort inverse la gravité dans un cylindre de 15 mètres de rayon et de 30 mètres de haut centré sur un point de votre choix à portée. Toutes les créatures et tous les objets qui ne sont pas ancrés au sol, d'une manière ou d'une autre, tombent vers le haut jusqu'à atteindre le sommet de la zone affectée par le sort. Une créature peut faire un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité pour s'accrocher à un objet fixe situé à sa portée, afin d'éviter la chute.

Si un objet solide (comme un plafond) se trouve sur la trajectoire de la chute, les créatures et les objets le percutent comme lors d'une chute ordinaire vers le bas. Si un objet ou une créature atteint le sommet de la zone affectée sans heurter quoi que ce soit, il reste là, à osciller légèrement, pendant toute la durée du sort.

Une fois la durée du sort écoulée, les objets et les créatures affectés retombent au sol.








### Téléportation
```yml
title: "Téléportation"
description: "Le PJ et jusqu'à 8 créatures sont déplacées instantanément."
school: "Invocation"
level: 7
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "3 mètres"
components:
  verbal: true
  somatic: false
  material: false
  materials: ""
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
```
Ce sort vous transporte instantanément à la destination de votre choix, ainsi qu'un maximum de huit créatures consentantes de votre choix situées à portée et dans votre champ de vision ou bien ainsi qu'un unique objet situé à portée et dans votre champ de vision. Si vous prenez un objet pour cible, il doit tenir dans un cube de 3 mètres de côté et il ne doit pas être porté ni transporté par une créature non consentante.

Vous devez choisir une destination connue, située sur le même plan d'existence que vous. C'est votre degré de familiarité avec la destination qui détermine vos chances d'arriver sur place. Le MJ lance 1d100 et consulte la table ci-dessous.

**Familiarité**. « _Cercle permanent_ » désigne un cercle de téléportation dont vous connaissez la séquence de symboles. « _Objet associé_ » indique que vous possédez un objet prélevé à la destination choisie au cours des 6 derniers mois, comme un livre sorti de l'étagère de la bibliothèque d'un magicien, les draps d'une suite royale ou un éclat de marbre arraché au tombeau secret d'une liche. « _Très familier_ » désigne un endroit où vous vous êtes souvent rendu, un lieu que vous avez soigneusement étudié ou un endroit que vous voyez au moment de l'incantation.

« _Vu à quelques reprises_ » correspond aux endroits que vous avez vus plus d'une fois, mais avec lesquels vous n'êtes pourtant pas très familiers. « _Vu une fois_ » représente un lieu vu une seule fois, éventuellement par magie. « Description » correspond à un endroit que vous connaissez seulement via la description d'autrui, aussi bien au niveau de son emplacement que de son apparence, éventuellement grâce à une carte. « _Destination factice_ » désigne les endroits qui n'existent pas, si par exemple vous avez tenté de scruter le sanctuaire d'un ennemi mais n'avez vu qu'une illusion ou si vous essayez de vous téléporter en un endroit familier qui n'existe plus.

**Sur place**. Vous et vos compagnons (ou l'objet téléporté) apparaissez exactement où vous le souhaitiez.

**À proximité**. Vous et vos compagnons (ou l'objet téléporté) apparaissez à une distance aléatoire de votre destination, éloignés dans une direction tout aussi aléatoire. La distance qui vous sépare de votre destination est de 1d10 × 1d10 % de la distance que le sort vous a fait parcourir. Par exemple, si vous essayez de vous téléporter à une destination située à 180 kilomètres de votre position, que vous arrivez à proximité, et que vous obtenez 5 et 3, vous allez arriver à 15 % de distance de votre destination, c'est-à-dire à 27 kilomètres. Le MJ détermine la direction dans laquelle vous vous êtes éloignés de la cible en lançant 1d8, le 1 représentant le Nord, le 2 le Nord-Est, le 3 l'Est, etc., jusqu'à faire le tour de la rose des vents. Si vous comptiez vous téléporter dans une cité portuaire et arrivez à 27 kilomètres au large de ses côtes, en pleine mer, vous pourriez bien avoir quelques ennuis.

**Zone similaire**. Vous et vos compagnons (ou l'objet téléporté) arrivez dans une zone différente de celle prévue, mais dotée de caractéristiques visuelles ou thématiques similaires. Par exemple, si vous comptiez regagner votre laboratoire, vous pourriez arriver dans celui d'un autre magicien ou dans une boutique d'alchimie qui possède nombre d'outils et d'appareils présents dans votre laboratoire. En général, vous apparaissez dans l'endroit ressemblant à votre destination le plus proche de celle-ci, mais comme le sort n'a pas de limite de portée, vous pouvez tout à fait arriver n'importe où sur votre plan d'existence.

**Incident**. La magie imprévisible du sort complique le voyage. Chaque créature téléportée (ou l'objet téléporté) subit 3d10 dégâts de force tandis que le MJ relance le dé pour savoir où vous arrivez (sachant qu'il peut se produire plusieurs incidents, chacun infligeant ses propres dégâts).

|Familiarité|Incident|Zone similaire|À proximité|Sur place|
|:-|:-:|:-:|:-:|:-:|
|Cercle permanent|-|-|-|01-100|
|Objet associé|-|-|-|01-100|
|Très familier|01-05|06-13|14-24|25-100|
|Vu à quelques reprises|01-33|34-43|44-53|54-100|
|Vu une seule fois|01-43|44-53|54-73|74-100|
|Description|01-43|44-53|54-73|74-100|
|Destination factice|01-50|51-100|-|-|





### Tempête de feu
```yml
title: "Tempête de feu"
description: "Feu qui inflige 7d10 dégâts et embrase les objets inflammables."
school: "Évocation"
level: 7
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "45 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Clerc
    - Druide
    - Ensorceleur/Sorcelame
```
Une tempête faite de nuages de feu ronflant se forme à l'endroit que vous avez choisi, à portée. La tempête occupe une zone composée d'un maximum de dix cubes de 3 mètres d'arête, que vous pouvez disposer comme bon vous semble. Chaque cube doit avoir au moins une face adjacente à celle d'un autre cube. Chaque créature de la zone doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. Celles qui échouent subissent 7d10 dégâts de feu, les autres la moitié seulement.

Le feu endommage les objets présents dans la zone et embrase les objets inflammables de la zone que personne ne porte ou ne transporte. Si vous le désirez, les flammes peuvent épargner la végétation présente dans la zone.




## Niveau 8

### Dominer un monstre
```yml
title: "Dominer un monstre"
description: "La cible est <em>charmée</em>, le PJ contrôle ses actions."
school: "Enchantement"
level: 8
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 heure"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: false
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous tentez d'envoûter une créature située à portée et dans votre champ de vision. Elle doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse, sans quoi elle est [_charmée_](/gerer-la-sante-du-personnage/#charme) par vous pendant toute la durée du sort. Elle dispose d'un [_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors du [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) si vous ou des créatures amicales envers vous êtes en train de la combattre.

Tant que la créature est [_charmée_](/gerer-la-sante-du-personnage/#charme), vous entretenez un lien télépathique avec elle qui persiste tant que vous vous trouvez sur le même plan d'existence. Vous pouvez utiliser ce lien télépathique pour donner des ordres à cette créature tant que vous êtes conscient (ce qui ne vous demande pas d'action). Elle fait de son mieux pour vous obéir. Vous pouvez lui donner un ordre simple et générique, comme «  _attaque cette créature_  », «  _cours jusque là-bas_  » ou « _va chercher cet objet_ ». Si elle ne reçoit pas de nouvelle instruction de votre part une fois l'ordre exécuté, elle se contente de se défendre et de se préserver au mieux.

Vous pouvez utiliser votre action pour prendre le contrôle total de votre cible et la diriger de façon précise. Jusqu'à la fin de votre prochain tour, elle exécute seulement les actions que vous choisissez et ne fait rien que vous ne lui ayez autorisé. Pendant cette période, vous pouvez aussi lui faire exécuter une réaction, mais vous devez pour cela également dépenser votre propre réaction.

À chaque fois que la cible subit des dégâts, elle a droit à un nouveau [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Sagesse contre le sort. Si elle le réussit, le sort prend fin.

**À plus haut niveau**. Si vous lancez ce sort en utilisant un emplacement de niveau 9, la durée devient « _concentration, jusqu'à 8 heures_ ».



### Éclat du soleil
```yml
title: "Éclat du soleil"
description: "Lumière aveuglante qui inflige 12d6 dégâts radiants."
school: "Évocation"
level: 8
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "45 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "du feu et un éclat d'héliotrope"
ritual: false
classes:
    - Druide
    - Ensorceleur/Sorcelame
    - Magicien
```
La chaude lumière du soleil illumine une zone de 18 mètres de rayon centrée sur un point de votre choix situé à portée. Chaque créature présente dans cette lumière doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution. Celles qui échouent subissent 12d6 dégâts radiants et sont <RT l="aveuglées" t="aveugle"/> pendant 1 minute. Les autres subissent seulement la moitié des dégâts et ne sont pas <RT l="aveuglées" t="aveugle"/> par le sort. Les vases et les morts-vivants sont affectés par un [_désavantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) lors de ce [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde).

Une créature [_aveuglée_](/gerer-la-sante-du-personnage/#aveugle) par le sort fait un autre jet de Constitution à la fin de chacun de ses tours. Dès qu'elle réussit, sa cécité disparaît.

Ce sort dissipe toutes les ténèbres issues d'un sort présentes dans la zone.




### Mot de pouvoir étourdissant
```yml
title: "Mot de pouvoir étourdissant"
description: "La cible, qui possède moins de 150  PV, est <em>étourdie</em>."
school: "Enchantement"
level: 8
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "18 mètres"
components:
  verbal: true
  somatic: false
  material: false
  materials: ""
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous prononcez un mot de pouvoir capable de submerger l'esprit d'une créature située à portée et dans votre champ de vision. Elle en est abasourdie. Si elle possède 150 points de vie ou moins, elle est [_étourdie_](/gerer-la-sante-du-personnage/#etourdi), sinon le sort est sans effet.

Une cible [_étourdie_](/gerer-la-sante-du-personnage/#etourdi) a droit à un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution à la fin de chacun de ses tours. L'effet d'étourdissement se termine dès qu'elle en réussit un.






### Nuage incendiaire
```yml
title: "Nuage incendiaire"
description: "Nuage incandescent qui inflige 10d8 dégâts de feu aux créatures."
school: "Invocation"
level: 8
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "45 mètres"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Un nuage de fumée ondoyant constellé de braises rougeoyantes apparaît sous la forme d'une sphère de 6  mètres de rayon centrée sur un point à portée. Le nuage se répand en contournant les angles si nécessaire et la visibilité est nulle à l'intérieur. Le nuage persiste pendant toute la durée du sort ou jusqu'à ce qu'un vent fort ou modéré (au moins 15 km/h) le disperse.

Quand le nuage apparaît, chaque créature se trouvant à l'intérieur doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. Celles qui échouent subissent 10d8 dégâts de feu, les autres la moitié seulement. Une créature doit aussi effectuer ce jet quand elle entre dans la zone affectée pour la première fois du tour ou lorsqu'elle y finit son tour.

Le nuage s'éloigne de vous sur 3 mètres dans la direction de votre choix au début de chacun de vos tours.









### Tremblement de terre
```yml
title: "Tremblement de terre"
description: "Séisme qui ébranle les créatures et endommage les bâtiments."
school: "Évocation"
level: 8
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "150 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "une pincée de poussière, un caillou et un peu d'argile"
ritual: false
classes:
    - Clerc
    - Druide
    - Ensorceleur/Sorcelame
```
Vous créez une perturbation sismique en un point situé au niveau du sol, dans votre champ de vision et à portée. Pendant toute la durée du sort, d'intenses secousses agitent le sol dans un cercle de 30 mètres de rayon centré sur le point choisi. Elles ébranlent toutes les créatures et structures en contact avec le sol de cette zone.

Le sol affecté devient un terrain difficile. Toute créature qui se trouve en contact avec le sol et en pleine concentration doit réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Constitution sous peine de voir sa concentration brisée.

Quand vous lancez ce sort, et à la fin de chacun de vos tours passés à vous concentrer dessus, toutes les créatures en contact avec le sol de la zone affectée doivent réussir un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité ou tomber [_à terre_](/gerer-la-sante-du-personnage/#a-terre).

Le sort a des effets supplémentaires selon le terrain affecté. C'est au MJ de déterminer cela.

**Fissures**. Une fois que vous avez lancé le sort, des fissures s'ouvrent dans toute la zone affectée au début de votre tour suivant. 1d6 fissures s'ouvrent en des points choisis par le MJ. Chacune fait 1d10×3 mètres de profondeur pour 3 mètres de large et s'étend d'un bout de la zone sismique à l'autre. Une créature qui se tient sur l'emplacement d'une fissure en train de s'ouvrir doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. Si elle le rate, elle tombe dedans, sinon elle réussit à s'écarter à temps.

Une structure s'effondre automatiquement si une fissure s'ouvre sous elle (voir plus loin).

**Structures**. Les secousses infligent 50 dégâts contondants à toute structure en contact avec le sol au moment où vous lancez le sort et au début de chacun de vos tours jusqu'à la fin du sort. Si l'une d'elles tombe à 0 point de vie, elle s'effondre et blesse peut-être les créatures voisines. Une créature qui se trouve près d'un bâtiment en train de s'effondrer, à une distance égale ou inférieure à la moitié de la hauteur de ce bâtiment, doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. Si elle échoue, elle subit 5d6 dégâts contondants, elle tombe [_à terre_](/gerer-la-sante-du-personnage/#a-terre) et elle est ensevelie sous les décombres. Il faut réussir un test de Force (Athlétisme) DD 20 via une action pour y échapper. Le MJ peut modifier le DD en fonction de la nature des décombres. Si la créature réussit son jet de sauvegarde, elle subit seulement la moitié des dégâts, ne tombe pas [_à terre_](/gerer-la-sante-du-personnage/#a-terre) et n'est pas ensevelie.







## Niveau 9

### Arrêt du temps
```yml
title: "Arrêt du temps"
description: "Le PJ arrête le temps pendant 1d4+1 rounds pour tout le monde sauf lui."
school: "Transmutation"
level: 9
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "personnelle"
components:
  verbal: true
  somatic: false
  material: false
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous arrêtez brièvement le cours du temps pour tout le monde sauf vous. Le temps ne s'écoule plus pour les autres créatures, tandis que vous disposez de 1d4+1  tours d'affilée, pendant lesquels vous pouvez faire des actions et vous déplacer normalement.

Ce sort se termine si l'une des actions que vous effectuez lors de ce laps de temps ou l'un des effets que vous créez lors de ce laps de temps affecte une créature autre que vous ou un objet porté ou transporté par une créature autre que vous. Le sort se termine également si vous vous éloignez à plus de 300 mètres de l'endroit où vous l'avez lancé.





### Mot de pouvoir mortel
```yml
title: "Mot de pouvoir mortel"
description: "La cible, qui possède moins de 100  PV, meurt instantanément."
school: "Enchantement"
level: 9
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "18 mètres"
components:
  verbal: true
  somatic: false
  material: false
  materials: ""
ritual: false
classes:
    - Barde
    - Ensorceleur/Sorcelame
    - Magicien
    - Sorcier
```
Vous prononcez un mot de pouvoir capable d'obliger une créature située à portée et dans votre champ de vision à mourir instantanément. Si la créature choisie a 100 points de vie ou moins, elle meurt, sinon le sort n'a aucun effet.





### Nuée de météores
```yml
title: "Nuée de météores"
description: "4 explosions qui infligent 40d6 dégâts."
school: "Évocation"
level: 9
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "1,5 kilomètre"
components:
  verbal: true
  somatic: true
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Des orbes de feu flamboyants s'abattent au sol en quatre points de votre choix situés à portée et dans votre champ de vision. Chaque créature située dans la sphère de 12 mètres de rayon centrée sur chacun de ces points doit effectuer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) de Dextérité. Les sphères s'étendent en contournant les angles. Une créature qui rate son [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) subit 20d6 dégâts de feu et 20d6 dégâts contondants, les autres la moitié seulement. Une créature qui se trouve prise dans deux sphères à la fois ne subit qu'une seule fois les dégâts des météores.

Le sort abîme et embrase les objets inflammables de la zone s'ils ne sont pas portés ou transportés.







### Portail
```yml
title: "Portail"
description: "Crée une porte qui conduit à un autre plan d'existence."
school: "Invocation"
level: 9
concentration: true
casting_time: "1 action"
duration: "jusqu'à 1 minute"
range: "18 mètres"
components:
  verbal: true
  somatic: true
  material: true
  materials: "un diamant d'une valeur minimale de 5000 po"
ritual: false
classes:
    - Clerc
    - Ensorceleur/Sorcelame
    - Magicien
```
Vous invoquez un portail reliant un espace inoccupé, situé à portée et dans votre champ de vision, à un autre plan d'existence. Ce portail se présente sous la forme d'une ouverture circulaire de 1,50 à 6 mètres de diamètre, à votre guise. Vous pouvez orienter le portail dans la direction de votre choix et il persiste pendant toute la durée du sort.

Le portail a une face avant et une face arrière sur chaque plan où il apparaît. Pour voyager grâce au portail, il faut impérativement le franchir en passant par l'avant. Tout ce qui le traverse ainsi apparaît instantanément sur l'autre plan, dans l'espace inoccupé le plus proche du portail.

Les divinités et autres dirigeants planaires peuvent empêcher un portail né de ce sort de s'ouvrir en leur présence ou en n'importe quel point de leur domaine.

Quand vous lancez ce sort, vous pouvez prononcer le nom d'une créature spécifique (sachant que les pseudonymes, les titres et les surnoms ne fonctionnent pas). Si cette créature se trouve sur un autre plan que celui sur lequel vous vous trouvez, le portail s'ouvre dans ses environs immédiats et attire la créature en son sein. Elle réapparaît de votre côté du portail, dans l'espace inoccupé le plus proche. Cela ne vous donne aucun contrôle sur la créature, qui agit librement, comme le MJ le désire. Elle peut s'en aller, vous attaquer ou vous aider.





### Souhait
```yml
title: "Souhait"
description: "Modifie les fondements de la réalité ou réplique n'importe quel sort."
school: "Invocation"
level: 9
concentration: false
casting_time: "1 action"
duration: "instantanée"
range: "personnelle"
components:
  verbal: true
  somatic: false
  material: false
  materials: ""
ritual: false
classes:
    - Ensorceleur/Sorcelame
    - Magicien
```
Le souhait est le plus puissant des sorts qu'une créature mortelle puisse lancer. Vous pouvez modifier les fondements de la réalité selon vos désirs, simplement en prononçant quelques mots.

L'utilisation basique de ce sort consiste à dupliquer les effets de n'importe quel sort de niveau 8 ou moins. Vous n'avez alors pas besoin de remplir les conditions requises, pas même de fournir les composantes matérielles onéreuses, le sort fait tout simplement effet.

Sinon, vous pouvez créer l'un des effets suivants, au choix.
* Vous créez un objet d'une valeur maximale de 25000 po qui n'a rien de magique. Il doit mesurer au maximum 90 mètres dans chaque dimension et apparaît en un emplacement inoccupé situé au sol et dans votre champ de vision.
* Vous permettez à un maximum de vingt créatures situées dans votre champ de vision de récupérer la totalité de leurs points de vie et vous mettez fin à tous les effets les affectant, tel que décrit dans le sort de <ST s="restauration-superieure"/>.
* Vous conférez à un maximum de dix créatures situées dans votre champ de vision une résistance à un type de dégâts de votre choix.
* Vous conférez à un maximum de dix créatures situées dans votre champ de vision l'immunité contre un unique sort ou un autre effet magique pendant 8 heures. Par exemple, vous pouvez vous immuniser, ainsi que tous vos compagnons, contre l'attaque absorption de vie des liches.
* Vous défaites un unique événement récent en faisant relancer un jet de dé effectué au cours du round précédent (y compris lors de votre dernier tour). La réalité se modifie pour s'adapter au nouveau résultat. Par exemple, un souhait peut obliger un adversaire à relancer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) réussi, un ennemi à refaire son jet de critique ou un ami à rejouer un [jet de sauvegarde](/utiliser-les-caracteristiques/#jets-de-sauvegarde) raté. Vous pouvez attribuer un [_avantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) ou un [_désavantage_](/utiliser-les-caracteristiques/#avantage-et-desavantage) à la créature qui relance le dé et vous êtes libre d'appliquer le résultat du premier jet ou de la relance.

Ce sort peut également vous permettre d'accomplir des exploits dépassant le cadre des exemples précédents. Formulez votre souhait à votre MJ de la manière la plus précise possible. Le MJ dispose d'une grande liberté pour gérer ce genre de cas. Plus le souhait est important, plus il y a de chances que quelque chose tourne mal. Le sort peut tout simplement échouer, avoir des effets partiels seulement ou s'accompagner de conséquences inattendues en raison de la manière dont vous l'avez formulé. Par exemple, si vous souhaitez qu'un adversaire soit mort, vous pouvez très bien être projeté en avant dans le temps, à une période où il est décédé, ce qui, en pratique, vous élimine de la partie en cours de jeu. Et si vous souhaitez obtenir un objet magique légendaire ou un artefact mythique, vous pourriez très bien être instantanément transporté en sa présence, et en celle de son propriétaire actuel.

Le stress lié à l'incantation d'un _souhait_ pour faire autre chose que répliquer un autre sort vous affaiblit grandement. À tel point que vous subissez 1d10 dégâts nécrotiques par niveau de sort à chaque fois que vous lancez un autre sort par la suite, et ce jusqu'à ce que vous ayez terminé un repos long. Il est absolument impossible de réduire ces dégâts ou de les empêcher, de quelque manière que ce soit. De plus, votre Force tombe à 3 (si elle n'est pas déjà de 3 ou moins) pendant 2d4  jours. À chaque fois que vous passez une de ces journées à vous reposer et ne rien faire de plus que des activités légères, le temps de récupération qui vous reste diminue de 2 jours. Enfin, suite à ce stress, il y a 33 % de chances que vous ne puissiez plus jamais lancer _souhait_.



