## Usage

Le service rendu par l’exécution du code doit lui aussi fournir une garantie de liberté d’usage pour rendre effectif le commun. Ce point est particulièrement important pour les services disposant d’un monopole de fait, et dont la duplication du code source ne permettrait pas la duplication du service rendu[^12]. Deux cas illustrent cette possibilité : l’usage d’une interface avec des ressources privées (API, interaction avec un back-office…), et celui des plateformes numériques. Dans ce second cas, la prééminence de la valeur des effets de réseau par rapport à la valeur algorithmique rendent extrêmement difficile la duplication du service[^13].

#### Un commun minimal inclut des conditions générales d’utilisation qui permettent l’usage sans conditions autres que celles strictement nécessaires à l’opération du service et à la prévention des actes visant à réduire la capacité d’autres usages. {#cgu-larges}

#### _Recommandation pour les acteurs publics : transformer les contraintes juridiques en un espace d’information pour les usagers, en utilisant un langage clair et lisible qui catégorise les conditions d’usage selon leurs questionnements. [Exemple](https://mes-aides.gouv.fr/cgu)._ {#cgu-larges-recommandation-public}

Au-delà des garanties juridiques, des garanties techniques sont appropriées pour que la liberté d’usage puisse être effective. Dans le cas d’un commun minimal, une qualité de service insuffisante peut être remédiée par la création d’un service alternatif sur la base du code. Mais, dans le cas d’un commun contributif, il faut que l’instance à travers laquelle la communauté collabore soit fonctionnelle. Si le service est en maintenance permanente, même les CGU les plus ouvertes ne pourront en permettre l’usage.

#### Un commun contributif inclut un engagement sur un taux de disponibilité du service pour ses usagers (SLA[^14]). Pour ne pas freiner l’évolution du service, ce SLA doit évoluer dans le temps et être interprété comme un « budget de contribution[^15] ». {#budget-contribution}

#### _Recommandation pour les acteurs publics : pondérer le SLA selon le nombre d’usagers, en appliquant une formule de type (100 % - SLA) ⨉ nombre d’usagers &lt; v, v étant fixé selon l’importance du service ressentie par les usagers._ {#budget-contribution-recommandation-public}

[^12]: Par exemple, le moteur de Wikipédia, Mediawiki, est un logiciel libre qui peut être et qui est largement dupliqué. Pour autant, dupliquer le service rendu par Wikipédia serait extrêmement complexe, car les usagers — et donc les contributeurs — connaissent tous « Wikipédia ». Un doublon offrant exactement les mêmes fonctionnalités n’aurait aucune chance de concurrencer efficacement le service rendu.

[^13]: C’est pourquoi une migration d’un service comme Twitter vers une alternative comme Mastodon est peu probable : même si l’algorithmique permettant la distribution du réseau sur plusieurs instances est plus avancée qu’un service monolithique, la valeur du service provient avant tout de la contribution de ses utilisateurs. Le retour sur investissement pour chaque utilisateur individuel va en faveur de continuer à utiliser le service qui détient le plus d’utilisateurs, car le coût (se retrouver isolé) ne vaut pas les bénéfices (meilleures fonctionnalités).

[^14]: Un [SLA](https://fr.wikipedia.org/wiki/Service-level_agreement) peut s’exprimer en pourcentage de demandes traitées par unité de temps. On peut ainsi par exemple s’engager à une disponibilité de 99,9 % par mois, ce qui signifie que 99,9 % des demandes sont traitées sans erreur de la part du système.

[^15]: Dans [cette vue](https://landing.google.com/sre/interview/ben-treynor.html), inspirée de la mouvance Site Reliability Engineering, au lieu d’interpréter un engagement de disponibilité de 99,9 % par mois comme un minimum acceptable qui devrait tendre vers 100 %, on considère qu’on peut déployer des améliorations qui comprennent un risque opérationnel jusqu’à ce qu’elles aient mené à des erreurs sur 0,1 % des demandes au maximum.
