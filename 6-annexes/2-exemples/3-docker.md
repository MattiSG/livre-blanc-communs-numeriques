## Docker

Docker est un logiciel libre de gestion de paravirtualisation qui permet d’isoler et d’allouer dynamiquement des ressources physiques. Il garantit la portabilité d’application et de leur dépendances à l’aide de containers et s’impose comme un standard de facto.

Docker n’est pas un commun : la société commerciale docker inc.garde les rôles clef de la gouvernance des différents produits et services, même si elle est particulièrement ouverte et sa gouvernance transparente.et assumée, comme le rôle du Benevolent dictator for life (BDFL) assuré par le fondateur Solomon Hykes[^25].

### Produits et services

hub.docker.com : service propriétaire de docker Inc. qui regroupe des contributions libres de la communauté github [Alternative possible : ([https://github.com/nathanleclaire/tarzan](https://github.com/nathanleclaire/tarzan)) mais qui perd l’intérêt du service centralisé]

*   images communautaires : possible pour tous avec inscription au préalable
*   images officielles gérées par docker.com aveec un processus d’habilitation partners@docker.com et une équipe de [maintainers](https://github.com/docker-library/official-images/blob/master/MAINTAINERS) (à noter, d’une société tierce) : [http://www.infosiftr.com](http://www.infosiftr.com)

Le logiciel libre docker:

*   Une gouvernance du projet, non démocratique, mais transparente et ouverte à des extérieurs de dockers.inc via GitHub. GitHub est l’outil de collaboration et de travail, pas d’un simple dépôt de code ouvert a posteriori.
    *   Une gouvernance générale de tous les projets avec un [_governance advisory board_](https://docs.docker.com/opensource/governance/dgab-info/)qui reprend 6 principes d’une gouvernance ouverte.
    *   Un détail des rôles et une consolidation automatique des mainteneurs des différents projets : [https://github.com/docker/opensource/blob/master/MAINTAINERS](https://github.com/docker/opensource/blob/master/MAINTAINERS)

La communauté docker, qui gère essentiellement la documentation et les forums:

*   [https://github.com/docker/docker.github.io](https://github.com/docker/docker.github.io) avec code et contenu disponible sous apache 2.0

Analyse

Pour appliquer la grille de lecture proposée dans ce document,

| **Constituant** | **Modalités de contribution** | **Modalités d’animation** | **Commun** |
| --- | --- | --- | --- |
| **Usage (hub.docker)** | Utilisation du hub : docker pull | Images officielles vs personnelles | Plateforme mise à disposition par docker Inc. et gouvernance partagée sur les images officielles |
| **Code source (docker CE)** | Pull Request | Fichier MAINTAINERS | Hébergé sur github |
| **Données (hub.docker)** | Création de repository sur le hub |  |  |
| **Communauté** | Documentation rédigée par la communauté |  | Contrôlée par docker Inc., mais sous licence apache 2.0 |
| **Marque** |  | La commande docker pointe naturellement vers le hub docker propriété de docker Inc. | Propriété de docker Inc. |
| **Stratégie** |  |  | MAINTAINERS.md : Docker Inc. garde le dernier mot |
| **Acteur** | Individus |  | Docker inc. |

[^25]: Rare sont les projets open-source qui soient démocratiques. Linux est toujours assuré par Linus, et l&#039;exemple de la gouvernance la plus démocratique reste l&#039;
