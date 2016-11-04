# Référentiel CMS

## Méthodologie d'utilisation du référentiel CMS

### Champ d'application

Le référentiel s'applique à un outil si&nbsp;: 
- l'outil permet d'éditer des contenus&nbsp;;
- les contenus saisis ont vocation à être rendus publics à un groupe d'utilisateurs. 

Ainsi, un formulaire de contact sur un site n'entre pas dans le champ d'application. Le contenu généré n'a pas une vocation de communication avec d'autres utilisateurs, mais uniquement avec le propriétaire du site.

#### Permissions des auteurs

Les outils d'édition permettent de définir différents niveaux de permissions. Les critères du référentiel technique ne prennent pas en compte les restrictions qui pourraient être imposées aux auteurs, via des configurations de permissions. Les critères doivent être compris et évalués sur l'ensemble de l'outil et non dans une configuration particulière de permissions.

Il est conseillé aux administrateurs des permissions d'utilisateurs de veiller à ce que les fonctionnalités qui permettent la création de contenus accessibles soient disponibles pour les auteurs.

### Méthodologie d'utilisation de ce référentiel

Pour certains critères, il est demandé de respecter le RGAA&nbsp;3&nbsp;2016. Dans ces cas, vous devez utiliser le RGAA pour contrôler les types de contenus concernés.

#### Exemple du [critère du référentiel CMS 6.6](criteres.md#c6-6)

Le critère demande à ce que les fonctionnalités d'édition avancée permettent de renseigner des informations d'accessibilité de niveau RGAA&nbsp;3&nbsp;2016 A. Dans ce cas, il faut repérer ces fonctionnalités dans l'interface et dans les zones d'édition.

Pour le cas d'un bouton d'insertion d'image qui ouvre une boîte de dialogue, vous devez vous référer à la thématique Images du RGAA&nbsp;3&nbsp;2016 et vérifier que les informations nécessaires sont éditables par les auteurs.

Le critère 1.3 du RGAA&nbsp;3&nbsp;2016 demande à ce que les images porteuses d'informations aient une alternative pertinente. Vous devez donc vous assurer que l'auteur peut définir cette alternative. Pour les images (balise <code>img</code>), l'auteur doit pouvoir éditer un champ dont la valeur sera implémentée dans l'attribut <code>alt</code> de l'image dans le contenu généré. Si la boîte de dialogue ne fournit que la possibilité de choisir l'image, mais n'offre aucun autre champ permettant de saisir une alternative, alors la fonctionnalité n'est pas conforme.

#### Exemple du [critère du référentiel CMS 5.1](criteres.md#c5-1)

Le critère demande à ce que l'outil propose un test de l'accessibilité des contenus. Dans ces cas, l'outil doit créer des tests pour tous les critères du RGAA&nbsp;3&nbsp;2016, même les tests non automatisables et qui nécessiteraient une validation humaine par la suite. 

Par exemple, selon la thématique Cadres du RGAA&nbsp;3&nbsp;2016, un cadre doit posséder un <code>title</code> renseigné. L'outil doit alors contrôler la présence de l'attribut <code>title</code> sur tous les cadres insérés par l'auteur.

Le critère 2.2 du RGAA&nbsp;3&nbsp;2016 demande à ce que ce <code>title</code> soit pertinent. Le test d'accessibilité doit en informer l'auteur et lui indiquer qu'il est possible que le <code>title</code> renseigné ne le soit pas.

#### Les pages à choisir pour l'évaluation

Pour évaluer la conformité au référentiel CMS, il est utile de construire l'échantillon à tester. Dans le cas du référentiel CMS, contrairement à RGAA&nbsp;3&nbsp;2016, ce sont les fonctionnalités plutôt que les pages qui sont au centre de l'évaluation. Il est donc normal de se baser sur les thématiques définies dans le référentiel CMS pour établir la liste des fonctionnalités à auditer dans ce cadre. Par exemple&nbsp;:
- les différents types de zones d'édition disponibles dans le CMS (éditeur de texte riche, champ de saisie simple etc.)&nbsp;;
- les templates disponibles par défaut&nbsp;;
- les objets pré-intégrés (images, textes, formulaires&hellip;)&nbsp;;
- les zones de paramétrages utilisateurs.

## Licence d'utilisation

Ce document est la propriété du Secrétariat général à la modernisation de l'action publique français (SGMAP). Il est placé sous la [licence ouverte 1.0 ou ultérieure](https://www.etalab.gouv.fr/licence-ouverte-open-licence), équivalente à une licence <i lang="en">Creative Commons BY</i>. Pour indiquer la paternité, ajouter un lien vers la version originale du document disponible sur le [compte <span lang="en">GitHub</span> de la DInSIC](https://github.com/DISIC).

## Sommaire du référentiel CMS

- [Introduction](intro.md)
- [Méthodologie d'utilisation du référentiel CMS](methodo.md)
- [Référentiel technique](criteres.md)
- [Cas particuliers](cas-particuliers.md)
- [Glossaire](glossaire.md)
- [Notes techniques](notes-techniques.md)
- [Mappage ATAG 2.0](mappage.md)
