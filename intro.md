# Référentiel CMS

## Introduction

Ce référentiel CMS vous est proposé dans le cadre des ressources accompagnant la prise en main de la version 3.0 du référentiel général d'accessibilité pour les administrations (RGAA&nbsp;3.0).

Le RGAA&nbsp;3.0 est composé d'un [document d'introduction](http://references.modernisation.gouv.fr/introduction-au-rgaa-0), d'un [guide d'accompagnement](http://references.modernisation.gouv.fr/guide-daccompagnement-0) et d'un [référentiel technique](http://references.modernisation.gouv.fr/referentiel-technique-0). Cet ensemble de documents a une portée réglementaire, puisqu'ils ont été rendus officiels par l'[arrêté du 29 avril 2015](http://www.legifrance.gouv.fr/affichTexte.do?cidTexte=JORFTEXT000030540064&dateTexte=20150921), lui-même venant préciser l'[article 47 de la loi 2005-102 du 11 février 2005](http://www.legifrance.gouv.fr/affichTexte.do?cidTexte=JORFTEXT000000809647&fastPos=1&fastReqId=1497340759&categorieLien=cid&oldAction=rechTexte#LEGIARTI000006682279) et le [décret 2009-546 du 14 mai 2009](https://www.legifrance.gouv.fr/affichTexte.do?cidTexte=JORFTEXT000020616980&categorieLien=id).

Les ressources complémentaires sont des supports sans valeur réglementaire et visent à vous aider à rendre vos contenus numériques accessibles et conformes au RGAA&nbsp;3.0.

### À qui s'adresse cette ressource&nbsp;?

Cette ressource est destinée aux développeurs d'applications web de gestion de contenus, ainsi qu'à toute personne souhaitant évaluer le niveau d'accessibilité de ces logiciels via la conformité à la norme internationale dédiée, ATAG&nbsp;2. Pour utiliser cette ressource, vous devez avoir une première expérience de l'accessibilité numérique, notamment une connaissance du RGAA et de ces mécanismes ou de WCAG&nbsp;2.0. En effet, ce référentiel, de part sa nature très technique, ne peut être correctement et efficacement appréhendé que par une personne familière des principes d'accessibilité numérique. De plus, une connaissance des mécanismes et fonctionnalités des outils d'édition de contenus web est nécessaire pour la compréhension des critères et des cas d'applications de ces derniers.

Ce référentiel est applicable à toute interface web permettant à des auteurs de créer des contenus à destination d'utilisateurs, notamment à des fins de communication. 

Par exemple, entrent dans le champ d'application&nbsp;: les CMS (systèmes de gestion de contenus), les LCMS (systèmes de gestions de contenus pédagogiques), les wikis, les <span lang="en">webmails</span>, les forums, les applications qui permettent de générer du contenu HTML, les applications d'édition de code source…

Il est nécessaire de savoir lire les langages HTML, CSS et JavaScript pour utiliser cette ressource. Par ailleurs, des tests complémentaires utilisant des technologies d'assistance peuvent être requis.

### Mode d'emploi du référentiel CMS

#### Avant toute chose&nbsp;: conformité au RGAA&nbsp;3.0

Avant de vous engager dans une démarche de mise en conformité ou d'évaluation d'un outil au regard des spécificités du référentiel CMS, la première étape est de s'assurer que l'outil lui-même est conforme au RGAA&nbsp;3.0. C'est la portée des trois premiers critères de ce référentiel&nbsp;: 

- Critère 1.1 [A] «&nbsp;L'interface respecte-t-elle les recommandations RGAA&nbsp;3.0 de niveau A&nbsp;?&nbsp;»
- Critère 1.2 [AA] «&nbsp;L'interface respecte-t-elle les recommandations RGAA&nbsp;3.0 de niveau AA&nbsp;?&nbsp;»
- Critère 1.3 [AAA] «&nbsp;L'interface respecte-t-elle les recommandations RGAA&nbsp;3.0 de niveau AAA&nbsp;?&nbsp;»

Selon le niveau envisagé (A, AA, AAA), vous devez donc vous assurer que tous les éléments de l'interface respectent les critères requis du RGAA&nbsp;3.0.

Ces trois premiers critères de référentiel CMS doivent être considérés comme des prérequis nécessaires avant toute procédure supplémentaire (évaluation ou développement). En effet, si l'interface elle-même n'est pas accessible, ses capacités à produire et à accompagner dans la production de contenus accessibles seront nécessairement impactées.

#### Les thématiques

Le référentiel CMS est découpé en 8 thématiques.

Dans le cadre d'une mise en conformité d'un outil, ces thématiques peuvent être prises indépendamment les unes des autres et ainsi constituer des axes de développement. Ceci permet de concentrer un développement sur une problématique particulière (par exemple, l'enrichissement de la documentation) et éventuellement gérer une priorisation des améliorations.

Dans le cadre d'une évaluation, ces thématiques vont permettre de gérer le travail en plusieurs unités de sens. À la différence d'une évaluation dans le cadre du RGAA, ce n'est plus la notion de pages qui importe, mais de fonctionnalités. Ainsi, ces thématiques vont permettre de saisir rapidement le type de fonctionnalités à rechercher pour les évaluer et de construire l'échantillon à tester.

Pour plus d'informations, se reporter à la [méthodologie d'utilisation du référentiel CMS](methodo.md).

#### Glossaire

Pour préciser et aider à la compréhension, un glossaire permet de définir certains termes. Chaque terme défini dans le glossaire est lié directement depuis la liste des critères.

####  Cas particuliers

Plusieurs critères du référentiel CMS font référence à des cas particuliers permettant de préciser l'objectif du critère et la façon dont il doit être appliqué en excluant les cas qui ne relèvent pas de l'application dudit critère. Ce document liste l'ensemble des cas particuliers pour lesquels le critère concerné est non applicable.

#### Notes techniques

Les notes techniques donnent des explications pour la prise en charge de certains critères qui peuvent être complexes. Les notes techniques permettent de donner des informations supplémentaires pour permettre de mieux comprendre les critères concernés.

### Le référentiel CMS et le RGAA&nbsp;3.0

Alors que le RGAA&nbsp;3.0 est un référentiel permettant de vérifier la conformité aux normes internationales WCAG&nbsp;2, le référentiel CMS est lui basé sur la norme ATAG&nbsp;2.

La construction des critères du référentiel CMS est calquée sur celle du RGAA&nbsp;3.0&nbsp; et respecte les règles suivantes&nbsp;:
- un critère ou un test pose une question&nbsp;;
- un critère ou un test ne pose qu'une question et n'attend qu'une réponse (note&nbsp;: pour un test, cette règle peut avoir certaines exceptions) ;
- lorsque la réponse est positive, le critère est conforme&nbsp;;
- un critère est lié à une ou plusieurs recommandations ATAG&nbsp;2&nbsp;.

#### À propos d'ATAG&nbsp;2

ATAG&nbsp;2 est la norme internationale qui décrit les règles d'accessibilité pour les outils d'édition. Cette norme s'intéresse à la capacité d'un outil d'édition à produire du contenu accessible et à accompagner les auteurs dans la création de contenus accessibles.

WCAG&nbsp;2 s'intéresse à l'accessibilité des contenus tels qu'ils sont délivrés aux publics (par exemple un site web ou une application web) et fournit donc les règles à respecter (structure, balises, attributs, propriétés, présentation&hellip;) pour qu'un contenu soit accessible. ATAG repose sur les règles WCAG&nbsp;2 pour décrire des fonctionnalités que doivent posséder les outils d'édition. Par exemple, un critère va demander à ce que l'outil permette d'éditer, pour un élément donné, toutes les propriétés nécessaires qui permettent de rendre l'élément accessible. C'est alors à WCAG&nbsp;2 qu'il faut faire référence, puisqu'il définit les propriétés nécessaires et les éventuelles valeurs d'un élément pour qu'il soit accessible.

### Déclaration de conformité 

La déclaration de conformité doit indiquer tous les éléments qui ont permis de réaliser les tests&nbsp;: 
- les agents utilisateurs&nbsp;;
- les systèmes d'exploitation&nbsp;;
- les technologies d'assistance.

#### Niveaux de conformité

Tout comme pour RGAA&nbsp;3.0, les critères du référentiel CMS appartiennent a un des 3 niveaux de conformité : A, AA, AAA. Le niveau de conformité de l'outil est déduit des critères conformes.

#### Types de conformité

On distingue 2 types de conformité&nbsp;:
- Conformité&nbsp;: lorsque l'outil seul est conforme.
- Conformité partielle&nbsp;:
  - lorsque l'outil ne peut être conforme que s'il est amélioré d'outils additionnels (par exemple l'outil ne dispose pas de fonction de test de l'accessibilité, mais utilise un outil tiers pour réaliser ces tests)&nbsp;;
  - lorsque l'outil est un agrégat d'outils : dans ce cas, chaque outil doit être évalué en tant qu'outil indépendant, la conformité unique ne peut être déclarée&nbsp;;
  - lorsque l'outil ne peut pas être conforme, dû à des limitations de la plateforme (par exemple, la plateforme ne dispose pas de [services d'accessibilité](glossaire.md#Gservicesaccessibilite)).

Pour les deux premiers cas de conformité partielle, la déclaration doit contenir la liste des outils ou <span lang="en">plugins</span> additionnels nécessaire pour assurer la conformité.

### Ressources pour le référentiel CMS

- [Grille d'évaluation référentiel CMS (ods, 36ko)](grille-ATAG.ods)
- [Correspondance des critères ATAG 2.0 - Référentiel CMS](mappage.md)

### Ressources RGAA&nbsp;3.0 connexes

- [Référentiel technique RGAA 3.0](http://references.modernisation.gouv.fr/referentiel-technique-0)
- [Méthodologie de tests RGAA 3.0](http://disic.github.io/rgaa_methodologie/)

### Ressources externes et références

- [ATAG&nbsp;2.0 (ressource en anglais)](http://www.w3.org/TR/ATAG20/)
- [Introduction à ATAG (ressource en anglais)](http://www.w3.org/WAI/intro/atag.php)

## Licence d'utilisation

Ce document est la propriété du Secrétariat général à la modernisation de l'action publique français (SGMAP). Il est placé sous la [licence ouverte 1.0 ou ultérieure](https://www.etalab.gouv.fr/licence-ouverte-open-licence), équivalente à une licence <span lang="en">Creative Commons BY</span>. Pour indiquer la paternité, ajouter un lien vers la version originale du document disponible sur le [compte <span lang="en">GitHub</span> de la DInSIC](https://github.com/DISIC).

## Sommaire du référentiel CMS

- [Introduction](intro.md)
- [Méthodologie d'utilisation du référentiel CMS](methodo.md)
- [Référentiel technique](criteres.md)
- [Cas particuliers](cas-particuliers.md)
- [Glossaire](glossaire.md)
- [Notes techniques](notes-techniques.md)
- [Mappage ATAG&nbsp;2.0](mappage.md)
