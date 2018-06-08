===========
Les nations
===========
Les villes permettent de protéger vos constructions et aussi vos coffres.
Fonder ou rejoindre une ville, c'est essentiel pour votre développement.
Au plus votre communauté est grande, au plus vos richesses s'accumulent et vos constructions
évolues.

Les propriétés d'une nation
---------------------------

**Name:** Le nom de la nation qui peut être changé. Il doit être alphanumérique. (Par défaut entre 1 et 16 caractères)

**President:** Le joueur unique qui possède la nation.

**Ministers:** Ils sont des joueurs ayant les mêmes droits que le président. Ils ne peuvent pas ajouter / supprimer d'autres ministres ou changer le président. Nous appelons le personnel de la nation le président + ses ministres.

**Citizens:** Ils sont des joueurs qui sont dans la nation. Le président et les ministres sont aussi des citoyens.

**Region:** Le territoire de la nation. Il est considéré comme une surface horizontale qui est étendue verticalement. Cela signifie que vous ne pouvez pas définir une région entre les couches 20 et 130 par exemple (vous n'avez pas à vous préoccuper de la hauteur des points que vous allez sélectionner).

**Money:** Le montant d'argent que la nation a.

**Taxes:** Le montant d'argent que les citoyens (à l'exception des membres du personnel) doivent payer à la nation chaque jour. Si le joueur ne peut pas payer les taxes, il sera expulsé automatiquement de la nation.

**Upkeep:** La somme d'argent que la nation doit payer chaque jour pour ne pas tomber en ruines.

**Zones:** La liste de toutes les zones de la nation.

|


Créer une nation
----------------
Une fois que vous avez trouvé l'endroit idéal pour bâtir votre nouvelle vie, utilisez ``/n create <nom de la nation>``
pour créer une nouvelle nation. Cela créera votre nation, réclamant le seul bloc où vous êtes debout et le spawn sera là par défaut. Il vous en coûtera 50000 pigz. (Pour voir les coût ``/n cost``).

-----

⚠ Vous devez immédiatement mettre de l'argent dans la banque de votre nation (en utilisant ``/n deposit <montant>``) afin qu'elle ne soit pas perdue lors de la prochaine collecte de taxe journalière.

----

Vous pouvez ensuite revendiquer une zone pour votre nation en utilisant une hache d'or. Faites un clic droit pour spécifier un coin, et un clic gauche pour le coin opposé, puis utilisez ``/n claim`` pour le revendiquer au nom de votre nation. (N.B. Votre spawn doit se trouver dans cette première zone) Les nations n'ont pas besoin d'être carrées ou rectangulaires, vous pouvez ajouter des sections de terres à votre guise. Vous commencez avec 3072 blocs par habitant, après avoir utilisé ces blocs, vous pourrez en acheter plus éventuellement, à ce moment vous utiliserez ``/buyextra <montant>`` pour le faire, vous ne pourrez acheter qu’un certain nombre de blocs (le montant sera déterminé par votre administrateur, indiqué bientôt sur le ``/n cost``)

Liste des commandes Nations
---------------------------

*Attention!  L'annotation "(president) ou (staff)" à la fin d’une commande signifie qu'elle ne peut être exécutée que par le président ou un ministre de la nation donnée.*

/Nation
.......

========================================================= ===============================================================================================================================================
``/n info [nation]``                                      | Vous donne des informations sur la nation donnée ou sur votre nation si aucune n'a été spécifié.
                                                          | Dans le chat, vous pourrez modifier en cliquant sur les permissions et les flags.
``/n cost``                                               Vous donne des informations sur les coûts des nations, des Avant-postes, des taxes, etc.
``/n here``                                               Vous donne des informations sur la nation sur laquelle vous vous trouvez, le cas échéant.
``/n list``                                               Vous donne la liste de toutes les nations.
``/n create <nom>``                                       Créez une nation avec le nom donné. Le nom doit être alphanumérique et comporter entre 1 et 16 caractères.
``/n deposit <montant>``                                  Dépôt d'un montant d'argent spécifié dans la banque de votre pays.
``/n withdraw <montant>``                                 Retirer le montant spécifié de la banque de votre pays. (staff)
``/n claim``                                              | Faites votre pays revendiquer la zone que vous avez sélectionnée avec une hache d'or.
                                                          | La zone doit être adjacente à votre nation. (staff)
``/n claim outpost``                                      | Agrandissez votre nation réclamer le bloc sous votre position comme avant-poste. 
                                                          | Vous serez en mesure de réclamer normalement des blocs adjacents à celui-ci. 
                                                          | Coûte plus qu'une réclamation normale. (staff)
``/n unclaim``                                            | Faites en sorte que votre nation ne revendique plus la zone que vous avez sélectionnée avec une hache en or. 
                                                          | La zone doit se croiser avec la région de votre nation. (staff)
``/n invite <nom du joueur>``                             Demander à un joueur (il doit être connecté) de se joindre à votre nation. (staff)
``/n join <nation>``                                      Demandez au personnel de la nation indiqué de vous ajouter  dans cet nation.
``/n kick <nom du joueur>``                               Forcez le joueur précisé à quitter la nation. (staff)
``/n leave``                                              Quittez votre nation. Si vous êtes président, utilisez /n resign en premier.
``/n resign <nom du joueur successeur>``                  Définir le joueur donné en tant que nouveau président de la nation. (president)
``/n spawn <nom du spawn>``                               Vous téléporte au spawn précisé.
``/n setspawn <nom du spawn>``                            Créer un nouveau spawn sous vos pieds avec le nom défini. (staff)
``/n delspawn <nom du spawn>``                            Supprimer le spawn spécifié. (staff)
``/n buyextra <montant>``                                 | Faire en sorte que votre nation achète un nombre donné de blocs supplémentaires. 
                                                          | Ces blocs supplémentaires augmentent la limite de claim de votre pays. 
                                                          | Votre nation devra payer les frais de claim habituel pour intégrer ces blocs à votre territoire. (staff)
``/n minister add <nom du joueur>``                       Ajouter le joueur aux ministres de la nation. (president)
``/n minister remove <nom du joueur>``                    Retirer le joueur des ministres de la nation. (president)
``/n minister perm outsider build <true|false>``          Autoriser / Interdire aux personnes qui ne sont pas de votre pays de placer ou de casser des blocs dans votre nation. (staff)
``/n minister perm outsider interact <true|false>``       | Autoriser / Interdire les personnes qui ne sont pas de votre pays d'ouvrir les coffres, 
												          | les portes d'interrupteurs, les boutons poussoirs, etc. dans votre pays. (staff)
``/n minister perm citizen build <true|false>``           | Permettre / Interdire aux citoyens de votre nation de placer ou de casser des blocs dans votre nation. (staff)
``/n minister perm citizen interact <true|false>``        | Permettre / Interdire aux citoyens de votre nation d'ouvrir les coffres, les portes d'interrupteurs, 
                                                          | les boutons poussoirs, etc. dans votre pays. (staff)
``/n minister perm citizen flag pvp <true|false>``        Activer / Désactiver le pvp dans la région de votre pays. (staff)
``/n minister perm citizen flag fire <true|false>``       Activer / Désactiver la propagation du feu dans la région de votre pays. (staff)
``/n minister perm citizen flag mobs <true|false>``       Activer / Désactiver le spawn des monstres dans la région de votre nation. (staff)
``/n minister perm citizen flag explosions <true|false>`` Activer / Désactiver les explosions dans la région de votre pays. (staff)
``/n minister perm citizen flag open <true|false>``       Activer / Désactiver les personnes pouvant rejoindre librement votre nation. (staff)
``/n minister perm citizen flag public <true|false>``     Activer / Désactiver l'achat de zones pour les personnes qui ne sont pas de votre pays. (staff)
========================================================= ===============================================================================================================================================