# SwissAI-Tools

**Un catalogue public de ressources technologiques en lien avec la Suisse : API, MCP, modèles, logiciels, données et standards.**

Découvrir ce qui existe déjà, comprendre son utilité et retrouver sa source. L'objectif n'est pas d'inventer une nouvelle couche logicielle : **rendre les ressources existantes visibles, traçables et réutilisables**.

## Explorer le catalogue

| Accès | À quoi cela sert |
| --- | --- |
| [Catalogue de 139 ressources](CATALOGUE.md) | Vue lisible, organisée par type de ressource |
| [44 serveurs MCP](CATALOGUE.md#serveurs-mcp-44) | Accéder à des outils et données suisses via Model Context Protocol |
| [42 API](CATALOGUE.md#api-et-interfaces-de-programmation-42) | Intégrer des fonctionnalités ou des données dans une application |
| [Index JSON](catalogue/outils.json) | Filtrer les fiches par thème, format, provenance ou source |
| [Méthodologie et limites](METHODOLOGIE.md) | Comprendre ce qui est vérifié, inconnu ou soumis à conditions |

## Quelques recherches possibles

- **Langues et français suisse :** [SwissBERT](https://github.com/ZurichNLP/swissbert), [TERMDAT](https://api.termdat.bk.admin.ch/swagger/index.html), [SwissCoco](https://swissnlp.org/swiss-corpora-collection), [OFROM](https://ofrom.unine.ch/).
- **Intelligence artificielle et infrastructure :** [Apertus](https://apertus-ai.org/), [CSCS Inference API](https://docs.cscs.ch/services/inference/api), [Infomaniak AI](https://www.infomaniak.com/en/hosting/ai-services), [cloudscale.ch](https://www.cloudscale.ch/).
- **Comptabilité et entreprises :** [bexio API](https://docs.bexio.com/), [KLARA API](https://developer.klara.ch/), [Abacus API Hub](https://apihub.abacus.ch/), [Zefix](https://www.zefix.admin.ch/ZefixPublicREST/).
- **Transport et géographie :** [OJP Suisse](https://opentransportdata.swiss/en/cookbook/open-journey-planner-ojp), [CFF Open Data](https://data.sbb.ch/), [geo.admin.ch](https://docs.geo.admin.ch/get-started/overview.html).
- **Finance et paiement :** [SIX API Catalog](https://apiportal.six-group.com/default), [bLink](https://docs.blink.six-group.com/api-reference/introduction), [Swiss QR](https://www.six-group.com/fr/products-services/banking-services/payment-standardization/standards/qr-bill.html).
- **Santé et identité :** [CH Core FHIR](https://fhir.ch/ig/ch-core), [OFSP IDD API](https://api.idd.bag.admin.ch/swagger-ui/api-doc.html), [swiyu](https://swiyu.admin.ch/en/get-started).

## Comment savoir si un outil est suisse ?

Trois situations différentes existent :
1. **Origine** : développé par une institution ou un éditeur suisse.
2. **Exploitation** : service hébergé ou opéré dans une infrastructure située en Suisse.
3. **Utilité suisse** : outil indépendant donnant accès à une norme, une donnée ou un service suisse.

Ces critères ne se déduisent pas les uns des autres. Chaque fiche indique ses liens documentés à la Suisse et ses limitations.

## Organisation du dépôt

```text
SwissAI-Tools/
├── README.md
├── CATALOGUE.md
├── METHODOLOGIE.md
└── catalogue/
    └── outils.json
```

Une seule base structurée alimente la présentation publique ; les outils ne sont pas dispersés en dizaines de fichiers.

## Ce qu'il reste à explorer

Le catalogue actuel n'est **pas exhaustif**. Parmi les sources de découverte :
- [Open Source Software Catalogue fédéral et cantonal](https://www.opensource.admin.ch/) (environ 170 logiciels dans les résultats consultés) ;
- [I14Y — registre des APIs et métadonnées](https://www.i14y.admin.ch/en/catalog/dataservices) (environ 80 APIs visibles) ;
- [Swiss Public Data MCP](https://github.com/malkreide/swiss-public-data-mcp/blob/main/portfolio.json) (portefeuille communautaire de 42 MCP actifs déclarés) ;
- [La Poste suisse — API](https://developer.apis.post.ch/ui/apis) ;
- [SwissCoco — ressources linguistiques](https://swissnlp.org/swiss-corpora-collection).

Ces chiffres décrivent les **catalogues sources**, pas des ressources déjà intégrées à SwissAI-Tools. Ils peuvent changer.

**Dernière actualisation du registre : 16 novembre 2026.** Les entrées reposent sur des documentations et dépôts publics consultés, sans garantie d'opérabilité technique individuelle.
