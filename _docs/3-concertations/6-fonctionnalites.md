---
title: 3.6 Configurer les fonctionnalités d'une concertation
category: 3. Concertations
order: 7
---

Les fonctionnalités sont les modules de participation que vous pous pouvez activer sur chacun des processus. Il existe 9 modules participatifs. Vous pouvez en activer autant que vous le souhaitez (et même plusieurs du même type sur un seul processus participatif). Ils sont tous configurables individuellement.


> Pour configurer les fonctionnalités, cliquez sur "Fonctionnalités" dans le sous-menu de la concertation. Une liste apparait montrant les fonctionnalités déjà activées. Les icônes de chaque fonctionnalité permettent de suivre les actions suivantes : Gérer, publier/dépublier, configurer, gérer les permissions, détruire.

> Pour ajouter une fonctionnalité, cliquez sur “Ajouter une fonctionnalité”.

> La plupart des fonctionnalités se configurent à deux niveaux :
- Au niveau général : cette configuration s'appliquera à n'importe quelle étape de la concertation.
- Par étape : cette configuration ne s'appliquera que lorsque cette étape est activée. C'est le cas des **messages d'annonces. Les annonces par étapes viendront se substituer à l’annonce générale quand l’étape est active.**


___

#### Cliquez sur le titre de la fonctionnalité pour accéder à son mode d'emploi :

**[Rencontres](#rencontres)** : Agenda de rencontres publiques, seul les administrateurs du processus participatif peuvent créer des rencontres. Les rencontres peuvent être associées à des catégories.

**[Propositions](#propositions)** : Selon la configuration, espace ouvert aux propositions des citoyens ou espace de consultation pour l’institution.

**[Budget](#budget)** : Pour paramétrer la mise en place d’un budget participatif avec un vote de propositions dans le secteurs d’enveloppes budgétaires.

**[Enquête](#enquete)** : Pour réaliser des enquêtes à l’aide de formulaires web complètement personnalisables. 4 options de champs : réponse courte, réponse longue, choix unique et choix multiples.

**[Page](#page)** : Pratique pour mettre à disposition des informations complémentaires sur le processus. On peut activer un espace de commentaire

**[Suivi](#suivi)** : Pour communiquer des résultats concernant le processus. Seuls les administrateurs peuvent en publier. Ils peuvent les associer à des catégories et lier des propositions qui ont émergé pendant le processus.

**[Débats](#debats)** : Pour conduire des débats (initiés par l'administrateur et/ou par les citoyens) à travers un fil de commentaire.

**[Tirage au sort](#tirage-au-sort)** : Pour tirer au sort de manière complètement aléatoire une proposition parmi d'autres.

**[Actualités](#actualites)** : Pour éditer des articles.



### Rencontres

Pour ajouter des rencontres, vous devez d'abord configurer le module "Rencontres". Pour cela, vous devez l'ajouter depuis le sous-menu "Fonctionnalité". L'écran de configuration du module "Rencontres" s'ouvre :
![config-rencontres]({{site.baseurl}}/uploads/3-6-4-back-config-rencontres.png)

Vous devez renseigner un titre, un rang d'affichage dans la barre de navigation, une annonce globale et par étape, cocher "Activer le module commentaire" si vous souhaitez laisser les utilisateurs commenter les rencontres , et également cocher "Bloquer les commentaires" si vous souhaitez empêcher les utilisateurs de commenter les rencontres (les commentaires laissés précédemment restent visibles).

Une fois que le module "Rencontres" a été configuré, vous pouvez créer des rencontres.
Pour cela, cliquez sur le module "Rencontres" dans le sous-menu à gauche.
Les icônes du tableau de bord des rencontres permettent d'effectuer les actions suivantes :
![config-rencontres]({{site.baseurl}}/uploads/3-6-5-dashboard-rencontre.png)

Pour créer une rencontre, cliquez sur "Nouvelle" puis l'écran de configuration d'une rencontre s'ouvre :
![config-rencontres]({{site.baseurl}}/uploads/3-6-6-back-creation-rencontre.png)
Les champs à renseigner sont :
- Titre
- Description
- Adresse : Numéro, nom de rue, code postal et ville. Les adresses sont ensuite géocodées via here.com qui utilise les services founis par Open Street Map.
- Lieu : nom du bâtiment, de la salle de réunion, etc.
- Données de localisation : Si besoin, des informations sur comment accéder à la salle (par exemple, "Utiliser l'accès sud"), etc.
- Heure de début et heure de fin
- Catégorie, si pertinent

Pour activer une rencontre, se rendre sur le tableau de bord des rencontre, cliquer sur l'icône "Inscriptions", cocher "Activer les inscriptions", renseigner le nombre de places disponibles (laisser à 0 pour un nombre illimité de places), le nombre de places réservées (pré-réservation, entrée sur place sans réservation, etc.) et indiquer les "Conditions d'inscription" (par exemple, "Entrée libre").
Sur cette fenêtre, via le menu "Exporter", il est également possible d'exporter la liste des inscriptions aux formats CSV, JSON ou EXCEL.
![config-rencontres]({{site.baseurl}}/uploads/3-6-9-back-config-inscription.png)


### Propositions

Pour configurer un module "Proposition", vous devez aller dans le sous-menu des fonctionnalités et cliquer sur "Ajouter une fonctionalité". L'écran de configuration du module "Propositions" s'ouvre (voir coincidance entre les champs en backoffice et l'affichage en front) :

![config-propositions]({{site.baseurl}}/uploads/3-6-1-back-config-prop.png)

![config-propositions]({{site.baseurl}}/uploads/3-6-2-front-config-prop.png)

Pour gérer les propositions - c'est-à-dire pour accepter/refuser des propositions, cliquez sur le module "Proposition" dans le sous-menu de gauche. Les trois actions possibles sont "Notes privées" (des notes qui ne sont visibles que par les admins), "Répondre" et "Visualiser".
Vous pouvez exporter les propositions aux formats CSV, JSON, EXCEL en cliquant sur "Exporter"
Il est également possible de faire des propositions officielles en cliquant sur "Nouvelle proposition".
Vous pouvez enfin importer des propositions d'un autre module proposition dans celui-ci en cliquant sur "Importer depuis une autre fonctionnalité". Un double de la proposition importée sera créée, sans les commentaires/votes de la proposition originale, et qui sera liée à la proposition originale.
![config-propositions]({{site.baseurl}}/uploads/3-6-3-back-gestion-prop.png)

### Budget

### Enquête

Vous devez d'abord configurer le module "Enquête" en indiquant à quelle(s) étape(s) l'utilisateur peut répondre à l'enquête.
Pour configurer l'enquête en elle-même, cliquez sur "Enquête" dans la barre des fonctionnalités sur la gauche ou sur l'icône "Crayon" dans le tableau de bord du module "Enquête".
Il n'est possible de configurer qu'une enquête par module "Enquête".
Plusieurs type de questions sont possibles. Chaque question peut être obligatoire ou non.
- Option unique : il faut indiquer plusieurs options de réponse ; l'utilisateur ne peut choisir qu'une seule réponse.
- Option multiple : il faut indiquer plusieurs options de réponse ; l'utilisateur peut choisir plusieurs réponses ; vous pouvez configurer le nombre de réponse maximum ; vous pouvez configurer des champs qui resteront libres, à l'utilisateur de les remplir.
- Réponse courte : champ de texte court
- Réponse longue : champ de texte long
- Tri : il faut indiquer plusieurs choix ; l'utilisateur devra les classer dans l'ordre souhaité.

Il est impossible de modifier une enquête qui a reçu au moins une réponse.

![config-enquete]({{site.baseurl}}/uploads/3-6-7-back-config-enquete.png)


### Page

Vous pouvez éditer des pages qui renseignent l'utilisateur sur la concertation en cours, les méthodes de participation, les objectifs, etc.
Pour ajouter une page, cliquer sur "Ajouter une fonctionnalité" dans le menu des fonctionnalité.
![config-page]({{site.baseurl}}/uploads/3-6-8-back-config-page.png)

### Suivi

Le module "Suivi" permet aux utilisateurs de l'avancement des réalisations (à l'échelle globale, par catégorie et / ou par sous-catégorie) de l'action liée à une concertation. Cette action correspond aux propositions dont la réalisation a été décidée suite à la médiation opérée à travers Decidim, soit directement (via un vote), soit indirectement (via des rencontres, des assemblées ou l'intervention des équipes politiques et techniques).

Les réalisations peuvent être transformées en projets ou décomposées en sous-projets, qui décrivent avec plus de détail les réalisation, et pour lesquels un statut d'exécution peut être défini.
Vous pouvez définir plusieurs statuts pour vos résultats qui permettront de rendre compte de l’état d’avancement. Le  nom ne sera visible que dans la partie administrateur, il vous permet de l’intégrer dans certaines étapes. À l’inverse la  description est le texte qui sera visible par les utilisateurs. Vous avez la possibilité de réaliser deux sortes d’actions : modifier ou supprimer.
Vous pouvez associer vos résultats à des catégories et des propositions qui les ont inspirés. Pour sélectionner plusieurs propositions :
- sous Windows ou Linux : Ctrl + clic gauche
- sous Mac : Cmd + clic

Pour réaliser une frise chronologique vous devez cliquer sur l'icône 'horloge'. Ainsi vous voyez apparaître une fenêtre qui affiche les étapes déjà en cours si elles ont été créées. Pour ajouter une nouvelle étape dans la chronologie cliquez sur [Nouveau élément de chronologie]

Les réalisations, projets et états peuvent être mis à jour manuellement par un fichier CSV via l'interface d'administration.

Pour configurer le module "Suivi", cliquer sur "Ajouter une fonctionnalité", sélectionner "Suivi" et s'ouvre le mune de configuration du module :

Pour ajouter un nouveau résultat, cliquez sur "Nouveau résultat" dans le tableau de bord du module "Suivi".

### Débats

Vous devez d'abord créer et configurer un module "Débats" en indiquant à quelle(s) étape(s) l'utilisateur peut créer un débat et/ou commenter (= participer) les débats.

Pour créer un débat d'origine officielle, cliquer sur la fonctionnalité "Débats" dans la barre des fonctionnalités sur la gauche ou sur l'icône "Crayon" dans le tableau de bord du module "Débats", puis cliquez sur "Nouveau débat"


![creer-debat]({{site.baseurl}}/uploads/3-6-10-creer-debat.png)

### Tirage au sort

La fonctionnalité "Tirage au sort" vous permet de sélectionner de manière aléatoire un certain nombre de propositions depuis un groupe de proposition.


### Actualités

La fonctionnalité "Actualités" permet de créer des articles mettant en lumière des derniers développements de la plateforme, actualités de la concertation, etc.
Les articles les plus commentés sont mis en avant sur la plateforme.

Vous devez d'abord créer un module "Actualités" et le configurer en autorisant ou non les commentaires des utilisateurs.

Pour créer un article, cliquez sur le module "Actualités" dans le menu de gauche et renseignez le contenu grâce à l'éditeur de texte.

![creer-debat]({{site.baseurl}}/uploads/3-6-11-creer-debat.png)



