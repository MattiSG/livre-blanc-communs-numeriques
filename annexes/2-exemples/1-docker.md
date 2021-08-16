## Docker

Docker est un logiciel libre de gestion de paravirtualisation qui permet d’isoler et d’allouer dynamiquement des ressources physiques. Il garantit la portabilité d’application et de leur dépendances à l’aide de containers et s’impose comme un standard de facto.

Docker n’est pas un commun : la société commerciale Docker Inc garde les rôles clef de la gouvernance des différents produits et services, même si elle est ouverte et transparente. Cette positione est assumée, comme l'illustre le rôle du Benevolent dictator for life (BDFL) assuré par le fondateur Solomon Hykes.

### Produits et services

#### hub.docker.com

Service propriétaire de Docker Inc qui regroupe des contributions de la communauté. Il existe au moins [une alternative](https://github.com/nathanleclaire/tarzan), mais qui perd l’intérêt du service centralisé.

- Images communautaires : possible pour tous avec inscription au préalable.
- Images officielles gérées par docker.com avec un processus d’habilitation partners@docker.com et une équipe de [mainteneurs](https://github.com/docker-library/official-images/blob/master/MAINTAINERS) (à noter, d’une société tierce : [infosiftr.com](http://www.infosiftr.com)).

#### Le logiciel libre Docker

- Une gouvernance du projet, non démocratique, mais transparente et ouverte à des extérieurs de Dockers Inc via GitHub. GitHub est l’outil de collaboration et de travail, pas d’un simple dépôt de code ouvert a posteriori.
- Une gouvernance générale de tous les projets avec un [_governance advisory board_](https://docs.docker.com/opensource/governance/dgab-info/)qui reprend 6 principes d’une gouvernance ouverte.
- Un détail des rôles et une [consolidation automatique](https://github.com/docker/opensource/blob/master/MAINTAINERS) des mainteneurs des différents projets.

#### La communauté Docker

La communauté gère essentiellement la documentation, les forums, et le site [github.com/docker/docker.github.io](https://github.com/docker/docker.github.io) avec code et contenu disponible sous apache 2.0

### Analyse

Pour appliquer la grille de lecture proposée dans ce document (version 2017) :

| **Constituant** | **Modalités de contribution** | **Modalités d’animation** | **Commun** |
| --- | --- | --- | --- |
| **Usage (hub.docker)** | Utilisation du hub : docker pull | Images officielles vs personnelles | Plateforme mise à disposition par Docker Inc et gouvernance partagée sur les images officielles |
| **Code source (docker CE)** | Pull Request | Fichier MAINTAINERS | Hébergé sur GitHub |
| **Données (hub.docker)** | Création de repository sur le hub |  |  |
| **Communauté** | Documentation rédigée par la communauté |  | Contrôlée par Docker Inc, mais sous licence apache 2.0 |
| **Marque** |  | La commande docker pointe naturellement vers le hub docker propriété de Docker Inc | Propriété de Docker Inc |
| **Stratégie** |  |  | MAINTAINERS.md : Docker Inc garde le dernier mot |
| **Acteur** | Individus |  | Docker Inc |
