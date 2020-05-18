================
Shops et métiers
================
********
Les pigz
********
Qu'est-ce que les pigz ?
========================
Le pigz est la monnaie utilisée en jeu.
Elle permet principalement de faire du commerce et d'acheter des terrains dans une ville.

Comment en gagner ?
===================
Pour gagner ces fameux pigz, il y a plusieurs solutions :

* Vendre ses objets avec d'autres joueurs.
* Rejoindre un ou plusieurs métiers.

Consulter ses pigz
==================
Pour consulter votre solde vous devez executer la commande suivante : ``/money``


*********
Les shops
*********
Aykraft est un serveur permettant d’échanger et de vendre des items entre joueur.
Mais il est également possible de mettre en place des « shops » c’est-à-dire des boutiques permettant de faire du commerce même lorsque le joueur n’est pas connecté.

La mise en place de ces shops nécessite plusieurs conditions mais garantis néanmoins le commerce sans aucune chance de se faire arnaquer. (C’est-à-dire payer et ne pas récupérer le biens achetés)

Créer un shop
=============
Pour créer un shop il faut:

- Appartenir à une ville
- Créer un plot de type shop en utilisant la commande ``/plot set shop``
- Poser un coffre sur le plot en question
- Coût 500 pigz
- Sélectionner dans sa main l'objet que l'on souhaite vendre
- Taper la commande ``/shop create <Nombre d'item à vendre ou acheter> <Prix d'achat> <Prix de vente>``
- Faire un clique droit sur le coffre

Voilà il ne vous reste plus qu'à vendre ou acheter !

Exemple:

Je souhaite vendre 64 stone pour 1000 pigz et acheter pour 200 pigz, je tape donc:

``/shop create 64 1000 200``

Puis je clique droit sur le coffre vide.

Il est possible de ne pas vendre ou de ne pas acheter, pour cela il faut remplacer le montant par 0.

La limite de shops disponibles diffère en fonction des grades.

***********
Les métiers
***********
Pour gagner de l’argent sur Alykraft, il est possible d’avoir des jobs, vous permettant ainsi de vous enrichir.

Il existe une liste de job différent, classaient par catégorie.

Vous pouvez obtenir et gérer vos métiers depuis le NPC présent au spawn.

Ces actions sont égalements possibles via des commandes.

Pour accepter à la liste des commandes et sélectionner un job il faut :

- Taper ``/jobs`` pour avoir la liste des commandes disponibles.
- Taper ``/jobs browse`` pour voir la liste des métiers disponibles ainsi que l'argent gagné en fonction du métier.
- Taper ``/jobs join <Nom du métier>`` Pour rejoindre le métier
- Taper ``/jobs leave <Nom du métier>`` Pour quitter le métier

Il est également possible de quitter l'ensemble de ses métiers: ``/jobs leaveall``

Vous pouvez voir l'avancée de vos métiers en tapant la commande ``/jobs stats <Nom du joueur>``