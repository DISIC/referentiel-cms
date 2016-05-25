# Notes techniques

## <a name="NT-c1.1.2.3"></a>Note technique pour les critères 1.1, 1.2 et 1.3 relative à la construction de l'échantillon de test

À l'image d'un audit d'un site web, la construction de l'échantillon pour l'audit RGAA d'un CMS doit se baser sur la nature essentielle des pages. À ce titre, il est recommandé pour ces tests, de choisir au moins, si elles existent, les types de pages suivantes&nbsp;: 

- les pages de la documentation (si la documentation est intégrée à l'outil)&nbsp;; 
- l'index de la documentation (s'il est différencié de la page de la documentation)&nbsp;;
- les pages de configurations globales du CMS (les paramètres généraux par exemple)&nbsp;; 
- les pages de configurations spécifiques (page de sélection d'un gabarit, page pour la configuration du menu, etc.)&nbsp;;
- les pages qui présentent les contenus non textuels (la gestion d'un bibliothèque multimédia par exemple)&nbsp;;
- les pages d'édition courantes (édition d'un article, édition d'une page…)&nbsp;; 
- toute autre page nécessaire à un auteur pour contribuer. 

## <a name="NT-c1.8.9.10"></a>Note technique pour les critères 1.8, 1.9, 1.10

Les outils d'édition peuvent proposer des fonctionnalités de transcodage d'un format d'entrée vers un format de sortie. L'objectif des critères 1.8, 1.9 et 1.10 est de s'assurer que toutes les fonctionnalités d'accessibilité sont préservées, lorsqu'il existe dans le format de sortie des mécanismes équivalents. Dans le cas inverse, l'auteur doit être prévenu des pertes éventuelles d'accessibilité liées à l'absence ou aux limitations propres au format de sortie.

Par exemple, le format txt a un support limité de l'accessibilité, car il ne prend en charge qu'un nombre limité de structures via des conventions de formatage. Ainsi, les titres peuvent être indiqués par une ligne vide avant et après le titre et les listes par un marqueur visible, un tiret par exemple.

Il convient donc de vérifier deux choses&nbsp;:

- Si le format de sortie est limité, l'auteur est-il prévenu des pertes potentielles d'accessibilité&nbsp;?
- Pour tous les mécanismes équivalents dans le format de sortie, les informations relatives à l'accessibilité sont-elles préservées ou adaptées (par exemple pour les images dans un format txt qui doivent être remplacées par leurs alternatives.)&nbsp;?

Exemple d'application : cas des indications de langues dans le format txt.

On évalue une fonctionnalité d'exportation vers le format txt. On constate que pour tous les mécanismes propres au format txt (titre, liste, alternatives d'images…) les informations sont préservées. On constate par ailleurs que l'outil prévient que des informations d'accessibilité pourraient être perdues.

Le critère est conforme.

Dans le format d'entrée (par exemple HTML), il y a des indications de langue qui n'ont pas d'équivalent dans le format de sortie en txt. Bien qu'il s'agisse d'une perte d'accessibilité, le critère, pour ce problème, reste conforme si l'auteur est prévenu. À lui de trouver une solution spécifique, par exemple en traduisant les termes, ou en proposant une version accessible.

## <a name="NT-c2.1"></a>Note technique pour le critère 2.1

Les modifications de configuration de l'interface incluent également les mises à jour.

Si l'interface permet de réaliser les mises à jour de l'outil, dans ce cas précis, il est admis que la réversibilité de l'action ne soit pas possible. Dans ce cas, l'auteur doit être averti du caractère irréversible des modifications et doit confirmer la modification, par exemple la mise à jour vers une nouvelle version, avant son exécution.

## <a name="NT-c4.1"></a>Note technique pour le critère 4.1

Bien qu'il existe dans le RGAA&nbsp;3.0 de nombreux tests pour évaluer l'accessibilité des éléments non textuels (présence des attributs obligatoires pour les éléments <code>img</code> ou <code>iframe</code> par exemple), ce test est différent.

En effet, la zone d'édition peut utiliser un balisage d'édition différent du balisage de sortie. Ce balisage d'édition peut être un balisage indépendant d'une technologie web standard et peut ne pas trouver de correspondance dans les critères du RGAA&nbsp;3.0 basés sur HTML.

Les attributs ou propriétés ne peuvent pas être prévisibles dans ce cas. Il est donc utile pour ce test, de réaliser des tests de restitution avec les lecteurs d'écran de la base de référence, pour s'assurer que les alternatives des contenus non textuels sont effectivement restituées.

## Licence d'utilisation

Ce document est la propriété du Secrétariat général à la modernisation de l'action publique français (SGMAP). Il est placé sous la [licence ouverte 1.0 ou ultérieure](https://www.etalab.gouv.fr/licence-ouverte-open-licence), équivalente à une licence <span lang="en">Creative Commons BY</span>. Pour indiquer la paternité, ajouter un lien vers la version originale du document disponible sur le [compte <span lang="en">GitHub</span> de la DInSIC](https://github.com/DISIC).

## Sommaire du référentiel CMS

- [Introduction](intro.md)
- [Méthodologie d'utilisation du référentiel CMS](methodo.md)
- [Référentiel technique](criteres.md)
- [Cas particuliers](cas-particuliers.md)
- [Glossaire](glossaire.md)
- [Notes techniques](notes-techniques.md)
- [Mappage ATAG 2.0](mappage.md)
