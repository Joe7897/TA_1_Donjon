# TA_1 Info : Donjon

Bienvenu aventurier dans ce jeu où il va falloir démontrer des skills en matière de _Click_ pour vaincre vos adversaire.
Ce jeu est un parfait _défouloir_. Après une longue journée de travail, quoi de mieux que de CLIQUER sur les boutons de votre souris pour vous libérer de tout les mauvais esprits.

## Modèle économique du jeu

Comme vous l'aurez remarqué, une souris ca s'use vite quand on la martèle de clique. C'est pourquoi nous avons bien évidemment pensé à faire des partenariats avec des marques de souris de Gamer tel que Razer qui seraient ravi de recommander notre produit pour vendre plus de souris. On pourrait même faire des partenariats avec des streameurs Twitch qui donneraient envie à leur communauté de casser leur souris également, et on pourrait imaginer mettre une bannière "Razer" à la fin du jeu pour inciter les utilisateurs à acheter une nouvelle souris. Ce modèle économique ne se veut absolument pas éthique, bien évidemment.

Plus sérieusement, ...

## Principe du jeu

Une fois le jeu lancé, vous arrivez sur une interface d'acceuil où vous pourrez voir écrit le nom du jeu, ainsi que 2 options :
  - Jouer !
  - Les monstres me font trop peur, Mais inutile d'appeler votre mère, si vous avez cliqué sur le launcher du jeu c'est que vous comptiez y jouer, ce bouton ne fera donc rien.

Une fois que vous aurez cliqué sur Jouer !, vous voilà _In game_.

Votre héros :
  - PV : 100
  - 3 capacités :
  - Attaquer, envoie une boule de feu qui inflige 1 pts de dégats
  - Soigner, qui vous rend 10 pts de vie
  - Fuir, si vraiment vous vous dégonflez mais cela compte comme une défaite alors n'ayez pas recours à cette option mauviète !

Le boss :
  - PV : 100
  - 1 capacité :
  - Toute les 5 secondes, le boss vous enverra un laser qui inflige 50 + 5*(nb_laser_déjà_lancé).
  
  Autant dire qu'à un moment il sera capable de vous _OneShot_ (lorsque les dégats atteigneront 100).
  
Votre objectif ? Terrasser le dragon (et sauver la belle princesse, mais ca, ca sera dans la version 2.0).

## Améliorations possibles du jeu

On pourrait imaginer plusieurs niveaux (un peu dans le style Mario Bros) que l'on débloque au fur et à mesure des boss que l'on arrive à vaincre, et une difficulté croissante des boss. 
Avec ce petit niveau, on un apercu du gameplay et il suffit de reproduire ce même scénario avec des boss de plus en plus dur à vaincre.
Une option "esquive" donnerait plus de skill au jeu également (à la place de "Soigner" par exemple)

## Bug Boule de Feu

Normalement, vous devriez l'observer, mais lorsque l'on clique trop vite sur Attaquer, certaines boules de feu restent figés.
C'est le seul bug que j'ai observé mais que je n'arrive pas à fixer.
