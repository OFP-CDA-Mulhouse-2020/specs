# Site de Paris sportifs
## Module 1 : conception graphique et logique (9 jours)

- Vous utiliserez un Adobe XD pour définir les guidelines de l’interface graphique.
- Vous utiliserez bootstrap 4 ou 5-alpha(a vos risques et périls). Dans un second temps il sera possible mais pas obligatoire de créer une maquette HTML. 
- La personnalisation de bootstrap sera faite ultérieurement. **Le projet de départ ne devra donc pas contenir de CSS spécifiques.**
- Vous modéliserez le diagramme de classes de l'application qui devra répondre aux problématiques métier suivantes:

## Concepts clés:

Ces spécifications sont susceptibles d'évoluer légèrement dans le temps.

### Utilisateur
Un utilisateur est une personne utilisant le site pour poser des paris. 
Il a un portefeuille qui contient une monnaie ( réelle ou virtuelle). 
Quand il prend un pari, le montant qu’il parie est débité de son compte. 
Quand il gagne un pari, le montant misé multiplié par la cote lui est reversé.

Chaque pari pris donne lieu a un paiement qu’il faut historiser.
Chaque pari gagné donne lieu a un paiement pour le joueur qu’il faut historiser.

### Concurrents, épreuve sportive et type de sports

- Une épreuve se déroule en un lieu et à une date précise.
- Si on décide de parier sur des sports US par exemple, il sera nécessaire de prendre en compte les décalages horaires.
- Dans ce cas il sera nécessaire de connaitre la localisation précise de l'évenement afin de pouvoir déterminer le décalage.
- Pour des raisons de simplicité, le pari doit se faire avant le début de l’épreuve.
- Une épreuve sportive oppose des adversaires.

Il existe deux types de sports:
- Sport individuel: le concurrent est une personne
- Sport d’équipe: le concurrent est un ensemble de personnes

Certains sports peuvent être à la fois des sports d’équipe et des sports individuels en fonction des circonstances:

- Le tennis en simple : sport individuel
- Le tennis en double : sport d’équipe
- Le tennis en coupe Davis : sport d’équipe 

Même dans un sport d’équipe, on peut parier sur la performance d’un joueur en particulier ( Neymar se roule au moins 12 fois au sol pendant la 1ere mi-temps) 🤣🤣🤣

Il sera également possible de regrouper plusieurs épreuves sportives en ensemble. Par exemple : 8 journée de ligue 1 UberEats pour le football , 1/8 de finale de Roland Garros pour le tennis etc.

### Pari

Un pari se fait sur une épreuve sportive.

Une épreuve contient une liste de plusieurs paris possibles. ( exemple foot, victoire équipe 1, match nul ou victoire équipe2 , joueur marque sur penalty etc…) 

### Sports pris en compte:

Dans un premier temps l’application devra gérer les sports suivants : 

#### Football
- 11 joueurs titulaires dans chaque equipe
- 5 remplacants dans chaque equipe

#### Handball
- 7 joueurs titulaires dans chaque equipe
- 7 remplacants dans chaque equipe

#### Formule 1
- 1 pilote par voiture 
- 2 voitures par equipe

#### Tennis
- 1 joueur contre 1 joueur en tournoi

#### Tennis de table:
- 3 joueurs par équipe
- chaque joueur joue 3 matchs 
- deux de chaque équipe jouent un double

