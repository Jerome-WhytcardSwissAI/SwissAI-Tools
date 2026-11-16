# SwissAI-Tools

**Le point d'entrée ouvert vers les outils, APIs, MCP, modèles, données, logiciels et normes de l'écosystème suisse.**

Ce dépôt sert à **trouver ce qui existe déjà en Suisse, comprendre à quoi cela sert et remonter à la source officielle**. Il ne prétend ni héberger les outils ni les certifier. La découverte reste ouverte à toutes les activités — IA, développement, langues, données publiques, géographie, finance, administration, etc.

## Explorer

- **[Catalogue lisible — 31 ressources](CATALOGUE.md)** : parcourir les outils classés par usage principal.
- **[Données structurées JSON](catalogue/outils.json)** : rechercher, filtrer et réutiliser les fiches depuis une application.
- **[Méthode et provenance](METHODOLOGIE.md)** : comprendre le lien avec la Suisse, les sources et les limites.

## Par où commencer ?

| Besoin | Quelques points d'entrée |
| --- | --- |
| Écrire en français suisse | [TERMDAT](https://api.termdat.bk.admin.ch/swagger/index.html), [OFROM](https://ofrom.unine.ch/), [Federal Writing Guidelines](https://github.com/swiss/swiss-federal-writing-guidelines) |
| Exploiter des modèles d'IA | [Apertus](https://www.swiss-ai.org/swiss-ai-projects), [Infomaniak AI Services](https://www.infomaniak.com/fr/support/faq/admin2/ai-tools) |
| Découvrir des MCP suisses | [Swiss Public Data MCP](https://github.com/malkreide/swiss-public-data-mcp), [termdat-mcp](https://github.com/malkreide/termdat-mcp) |
| Trouver des APIs suisses | [I14Y](https://apiconsole.i14y.admin.ch/), [opendata.swiss](https://handbook.opendata.swiss/fr/content/nutzen/api-nutzen.html), [OFS](https://statistik.admin.ch/fr/donnees/api) |
| Vérifier une entreprise | [Zefix](https://www.bj.admin.ch/fr/registre-du-commerce-zefix-et-regix) |
| Construire avec les géodonnées | [geo.admin.ch](https://www.geo.admin.ch/fr/interface-de-programmation-api), [swisstopo-mcp](https://github.com/malkreide/swisstopo-mcp) |
| Intégrer la comptabilité suisse | [SIX QR-facture](https://www.six-group.com/fr/products-services/banking-services/payment-standardization/standards/qr-bill.html), [Swissdec ELM](https://www.swissdec.ch/fr/elm) |
| Créer des interfaces suisses | [Design System](https://github.com/swiss/designsystem), [Bootstrap Switzerland](https://github.com/swiss/bootstrap-switzerland) |

## Ce qui est suisse — et ce qui ne l'est pas nécessairement

La mention « suisse » ne signifie pas toujours « hébergé exclusivement en Suisse ». Chaque fiche précise un ou plusieurs liens **documentés** : institution, organisation, infrastructure, données ou norme. Les clients MCP indépendants restent identifiés comme projets tiers.

## Arborescence

```text
SwissAI-Tools/
├── README.md              Accueil et exploration
├── CATALOGUE.md           Vue humaine du catalogue
├── METHODOLOGIE.md        Provenance et qualité des informations
└── catalogue/
    └── outils.json        Index structuré unique
```

## Évolution

Le catalogue est un **point de départ**, pas une liste close. Les ressources sont décrites à partir de sources vérifiables, avec date de révision et limites connues. L'ajout de nouvelles catégories n'est pas conditionné par une arborescence préétablie.

Les exemples, données de production, codes sources et clés restent chez leurs éditeurs. Le catalogue renvoie vers eux.

**Première révision : 2026-11-16.** Les fiches vérifient la documentation des offres ; les intégrations n'ont pas été testées de bout en bout.
