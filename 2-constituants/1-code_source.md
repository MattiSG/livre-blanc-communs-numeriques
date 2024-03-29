## Code source

Les services numériques sont en premier lieu des logiciels. Même si on ne peut par définition pas les réduire à cette essence technique, leur première nature est l’exécution d’un code informatique. Ce code, dans une forme lisible et exécutable, est donc un constituant évident à mettre en partage.

### Licence libre

Les règles applicables à un code source sont formalisées par des licences, c’est-à-dire des contrats par lequel le titulaire des droits d&#039;auteur définit les conditions dans lesquelles ce programme peut être utilisé, diffusé ou modifié. Certains types de licences, les licences libres, garantissent des droits au public : lecture, duplication, redistribution. Ces droits empêchent donc la réappropriation de l’existant.

**Une contrainte minimale est la mise à disposition du code source sous une licence libre[^9].**

**Recommandation opérationnelle : utiliser une licence EUPL ou l’une des licences mentionnées à l’article [D323-2-1 du code des relations entre le public et l’administration (CRPA)](https://is.gd/rYk7h7).**

### Clause de repartage {#repartage}

Néanmoins, les communs numériques ne peuvent être réduits à un logiciel. Comme on l’a vu, leur spécificité provient de l’existence d’une _communauté_. C’est bien cette communauté rassemblée autour du logiciel qu’il faut préserver pour éviter la réappropriation, active ou par désertion de la communauté à l’exception d’un acteur.

La réappropriation active ne peut être empêchée que par la mise en œuvre d’une clause de repartage [Aigrin, 2002]. Une telle clause garantit que des améliorations apportées au logiciel sont mises à disposition de la communauté, en rendant obligatoire la publication des modifications du code source. En l’absence d’une telle clause, il suffit de reprendre le code source de logiciels constituant des communs numériques et d’y ajouter une fonctionnalité attirante pour les utilisateurs sans partager le code qui ajoute cette fonctionnalité [Aigrin, 2002] pour déplacer la communauté vers cette nouvelle version [Verdier &amp; Murciano, 2015] qui n’est plus gouvernée par un commun, vidant de ce fait les communs originaux de leur substance. Une licence de repartage est donc la plus adaptée au cas des communs contributifs.

**Pour le services contributifs, la licence inclut la mise à disposition du code source avec une clause de repartage.**

**Recommandation opérationnelle : utiliser une licence Affero GNU Public License 3.**

### Sollicitation des intégrations {#solliciter-integration}

Au-delà de l’usage, la capacité des usagers à contribuer au service doit être préservée. L’usage de licences libres garantit le droit de modifier le code, mais la contribution signifie également l’évaluation systématique de ces modifications et leur intégration chaque fois que cela s’avère pertinent. Sans cette capacité à contribuer, les logiciels libres ne sont qu’une nouvelle forme de monologue.

**Une contrainte minimale est de fournir un moyen de solliciter l’intégration de modifications effectuées par un contributeur dans la base de code originelle.**

**Recommandation opérationnelle : exploiter les outils spécialisés dans le développement collaboratif, qui fournissent une plateforme consolidée permettant à la fois la mise à disposition du code et la contribution de code et de suggestions d’améliorations, comme [Framagit](https://framagit.org/), [GitLab](https://about.gitlab.com) ou [GitHub](https://github.com).**

### Engagements sur les intégrations {#delai-traitement}

Au même titre que l’usage, la « contribuabilité » des communs ne saurait être mesurée par la seule capacité technique à solliciter l’intégration de modifications. Un contributeur dont les sollicitations ne sont jamais traitées sera rapidement frustré et cessera de contribuer, et la visibilité publique de cette absence de réponse en découragera d’autres.

**Il est utile de prendre un engagement sur le délai de traitement[^10] des sollicitations d’intégration de modifications ainsi qu’une charte de communication[^11] avec les contributeurs potentiels, afin de garantir une atmosphère ouverte et engageante.**

**Recommandation opérationnelle : mettre en place et publier un règlement intérieur décrivant les modalités de gestion des sollicitations d’intégration de modifications[^12].**

### Documentation opérationnelle {#ops}

Dans cet objectif également, les modalités techniques qui permettent l’opération du service, au sens de son administration système, devraient être également documentées et partagées au même titre que le code source : si une seule personne (physique ou morale) a connaissance de l’infrastructure nécessaire à l’opération du service, le risque de réappropriation est présent.

**Une contrainte minimale est la documentation des modalités d'opération technique du service.**

**Recommandation opérationnelle : documenter de manière exécutable par le biais d’un [système de gestion de configuration](https://fr.wikipedia.org/wiki/Gestion_de_configuration_logicielle), qui permet de définir l’infrastructure comme du code.**

[^9]: Liste exhaustive disponible sur [opensource.org/licenses/alphabetical](http://opensource.org/licenses/alphabetical).

[^10]: Le « traitement » ne signifie pas forcément l’intégration, mais au moins une première évaluation indiquant si la contribution est bienvenue, ou justifiant le refus de son intégration en fournissant des références permettant l’amélioration de futures contributions. Ce délai devra être le plus court possible : au-delà de quelques jours, le sentiment n’est plus celui d’une discussion, et on perd la communauté.

[^11]: De telles chartes sont généralement dénommées _code of conduct_.

[^12]: Voir également « comment reconnaître les contributions » en annexe.
