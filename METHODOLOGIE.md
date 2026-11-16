# Comment enrichir un catalogue d'outils suisses sans confondre les faits

## Qu'est-ce qui entre dans le catalogue ?

Le terme « outil suisse » est ambigu. Il peut désigner :
- une application ou un logiciel développé par une organisation suisse ;
- une technologie exploitée dans une infrastructure située en Suisse ;
- une interface ou une base de données publiée par une institution suisse ;
- une ressource linguistique, un format ou une norme conçue pour la Suisse ;
- un connecteur tiers donnant accès à des sources suisses.

Ces liens ne sont **pas interchangeables**. Un MCP maintenu par une personne indépendante n'est pas un outil officiel de la Confédération parce qu'il interroge une API fédérale ; une entreprise suisse n'implique pas que toutes les données de son produit sont hébergées en Suisse.

## Ce qu'une fiche représente

Chaque entrée de `catalogue/outils.json` décrit :
- **l'identité** (identifiant stable, nom, site d'origine) ;
- **la fonction** (description courte, type et thèmes de recherche) ;
- **le lien avec la Suisse** (`swiss_relation`) ;
- **la provenance** (pages officielles, documentation ou dépôt de l'éditeur dans `sources`) ;
- **les limites** (accès, licences, différence entre une norme, une API et un service) ;
- **le moment de la révision** (`reviewed_at`).

Le type (`kind`) exprime le mode d'utilisation : `api`, `mcp`, `modele`, `service`, `infrastructure`, `bibliotheque`, `donnees`, `corpus`, `norme`, `ressource` ou `catalogue`. Les `topics` ne sont pas une classification fermée : de nouveaux sujets peuvent apparaître quand de nouveaux usages sont découverts.

## La différence entre preuve, possibilité et absence de preuve

Une API documentée n'implique pas qu'elle accepte des requêtes sans authentification. Une infrastructure en Suisse ne signifie pas qu'un utilisateur y choisit automatiquement une région suisse. Un logiciel dont le code est public ne signifie pas que les données auxquelles il accède sont librement réutilisables.

Une information non trouvée est notée comme inconnue, plutôt que remplacée par une promesse. Les mentions « accès commercial », « conditions à vérifier » ou « client indépendant » sont des informations utiles, pas des jugements sur la qualité.

## Recherche de nouvelles ressources

La découverte est ouverte : sites officiels, API de métadonnées I14Y, opendata.swiss, catalogue OSS de l'administration, GitHub, universités et fournisseurs suisses. Les ressources non encore documentées ne sont pas nécessairement exclues ; leur présence dans un catalogue général externe peut être un indice à examiner.

Les répertoires comme [I14Y](https://apiconsole.i14y.admin.ch/), [opendata.swiss](https://opendata.swiss/) et le [catalogue OSS fédéral](https://www.opensource.admin.ch/fr/) ouvrent de nouvelles branches de recherche. Ils ne sont pas des sources d'exhaustivité absolue.

## Couverture et entretien

Une revue peut porter sur la disponibilité du site, les changements de version ou de licence, le statut de maintenance d'un dépôt, l'apparition d'une nouvelle API, ou le passage d'un service payant à un autre mode d'accès. Une ressource obsolète reste parfois intéressante pour l'historique, mais son statut doit être explicite et daté.

La date `2026-11-16` désigne la consultation documentaire ayant servi à constituer la fiche ; **ce n'est pas une preuve d'exécution technique** de l'API, du MCP ou du logiciel.

## Cadre public

Ce dépôt public contient uniquement des descriptions originales et des liens vers des ressources publiques. Il ne contient aucun jeton API, secret d'authentification, contact personnel extrait d'une boîte mail ou copie d'un corpus dont les droits seraient incertains.

Aucune licence générale n'est présumée pour les ressources répertoriées. La licence du **catalogue lui-même** demeure à choisir par le propriétaire du dépôt.

## Recherche multi-domaines avec Parallel — 16 novembre 2026

L'élargissement a été réalisé en parallèle sur l'infrastructure suisse, les modèles IA, les langues, les bibliothèques, l'administration, les paiements, la comptabilité, la logistique, la santé, la mobilité et les sciences. Une recherche approfondie a complété les recherches ciblées.

Les résultats ont été rapprochés de la base existante et dédoublonnés par identifiant. **139 fiches** sont présentes, dont **44 MCP** et **42 API**.

Les MCP issus du [portefeuille suisse de données publiques](https://github.com/malkreide/swiss-public-data-mcp/blob/main/portfolio.json) sont décrits sur la base de son registre JSON : celui-ci déclare 42 serveurs actifs et indique une date interne de vérification du 18 août 2026. Les deux projets généralistes n'utilisant pas spécifiquement des données suisses et les projets archivés n'ont pas été importés sous la seule étiquette « données suisses ». Le niveau de maturité annoncé par l'éditeur n'a pas été testé ici.

Les autres projets ont été sélectionnés principalement à partir de documentation d'éditeur, d'organismes publics, d'universités et de dépôts officiels. Des pages peuvent évoluer ou disparaître : la présence d'une URL HTTPS et d'un titre dans une recherche ne constitue pas une validation automatique du service.

### Ce qui reste inconnu

- fonctionnement effectif de chaque API et de chaque serveur MCP ;
- sécurité et maintenance des intégrations communautaires ;
- conditions précises d'utilisation commerciale, de réutilisation de corpus et de traitement de données ;
- disponibilité des offres selon le compte et la région d'hébergement ;
- couverture des projets qui ne sont pas indexés publiquement.

Le catalogue conserve **les données utiles à l'exploration** sans transformer ces inconnues en affirmations.
