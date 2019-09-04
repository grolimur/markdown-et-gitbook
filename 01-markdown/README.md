# Markdown

| Carte d'identité |     |
| :--------------- | :-- |
| naissance | 2004 |
| parents | John Gruber, avec l'aide d'Aaron Schwartz |
| licence | BSD |

![](../img/markdown.svg)

Markdown est à la fois d'une syntaxe pour formater du texte et un logiciel écrit en Perl pour convertir du texte en HTML (Gruber, 2014). Depuis sa première publication, Markdown (logiciel de conversion) a été traduit dans beaucoup d'autres langages (Borboen, 2013).

La force de Markdown réside dans le fait que même accompagné du balisage léger qui le structure, un texte est parfaitement lisible.
Débarassé de toutes les fiortures auxquels on est habitué dans les traitements de texte et outils de présentation, on gagne en efficacité (et donc du temps) lors de la rédaction d'un document.
Markdown est aussi indépendant du logiciel dans lequel vous l'utilisez, ce qui ne vous rend pas captif d'un environnement.


## Syntaxe

Les règles de baslisage de Markdown sont peu nombreuses. Dans la version d'origine, il y en a exactement douze, dont deux concernent l'insertion de code et deux les liens (Gruber, 2013).

1\. [paragraphe](01-paragraphe.md)   
2\. [titres](02-titres.md)   
3\. [citations](03-citations.md)   
4\. [listes à puces](04-listes.md)   
5\. [code](05-code.md)   
6\. [ligne horizontale](06-ligne.md)   
7\. [liens hypertextes](07-liens.md)   
8\. [accentuation](08-accentuation.md)   
9\. [images](09-images.md)   
10\. [backslash](10-backslash.md)   

Par ailleurs, la syntaxe originale de Markdown étant vraiment minimaliste, plusieurs initiatives ont oeuvré pour l'étendre. Je ne citerais ici que

* [Multimarkdown](https://fletcherpenney.net/multimarkdown/) de Fletcher T. Penney
* [CommonMark](https://commonmark.org/) de John MacFarlane & [contributeurs](https://commonmark.org/#who), [sur lequel GitBook se base](https://docs.gitbook.com/content-editing/markdown)
* [Github Flavoured Markdown](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown), largement basé sur CommonMark et utilisé par Github et beaucoup d'éditeurs de texte supportant Markdown.

Ces "dialectes" de Markdown offrent un certain nombre d'extensions dont les suivantes:

11\. [tableaux](11-tableaux.md)   
12\. [liste de tâches](12-taches.md)   
13\. [retour à la ligne](13-retour-ligne.md)   

Nous allons découvrir tout cela ensemble par la pratique.   
Pour créer un document Markdown, n'importe quel éditeur de texte convient. Il est toutefois plus agréable d'utiliser un éditeur prenant en charge Markdown pour la coloration syntaxique. Voici une liste **subjective et non exhaustive** de tels logiciels.

| logiciel | licence | GNU/Linux | Mac OS X | Windows | site web |
| :------- | :------ | :-------: | :------: | :-----: | :------- |
| Abricotine | GPLv3 | oui | oui | oui | [https://abricotine.brrd.fr](https://abricotine.brrd.fr) |
| Atom | MIT | oui | oui | oui | [https://atom.io/](https://atom.io/) |
| ghostwriter | GPLv3 | oui | oui | oui | [https://wereturtle.github.io/ghostwriter/](https://wereturtle.github.io/ghostwriter/) |
| MacDown | MIT | - | oui | - | [https://macdown.uranusjr.com/](https://macdown.uranusjr.com/) |
| Mark Text | MIT | oui | oui | oui | [https://marktext.app/](https://marktext.app/) |
| Remarkable | MIT | oui | - | - | [https://remarkableapp.github.io/](https://remarkableapp.github.io/) |
| Zettlr | GPLv3 | oui | oui | oui | [https://www.zettlr.com/](https://www.zettlr.com/) |

Ces logiciels répondent à au moins un des deux critères suivants:

* je l'utilise
* il est listé dans l'annuaire EPFL des principaux logiciels libres ([https://enacit.epfl.ch/logiciel-libre/](https://enacit.epfl.ch/logiciel-libre/))


---

### Mise en pratique

- [ ] si ce n'est déjà fait, choisissez un logiciel pour rédiger vos documents Markdown

---

### Notes personnelles
