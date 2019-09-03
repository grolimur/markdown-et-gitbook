## Git

![](../img/git.svg)

Avant de parler de GitBook, il convient d'expliquer ce qu'est git.

> Git est un système de gestion des versions décentralisé pour suivre les modifications dans le code source au cours du développement d'un logiciel. Il est conçu pour coordoner le travail plusieurs développeurs, mais il peut être utilisé pour suivre les modifications dans dans des fichiers. [...]

> Git a été créé par Linus Torvalds en 2005 pour le développement du noyau de Linux, quelques autres développeurs dudit noyau ayant contribué au développement initial.

> (*trad. de* Wikipedia contributors, 2019)

L'idée est de pouvoir revenir facilement à une version précédente d'un document.
Le suivi des modifications avec Git s'applique parfaitement aux fichierx texte (Markdown, txt, LaTeX, etc.). Il est par contre peu adapté aux fichiers binaire (Word, PowerPoint, images, etc.). Exception notable parmi les images, les fichiers SVG peuvent parfaitement être versionnés à l'aide de Git.

Git doit être installé sur l'orindateur où il doit être utilisé et il faut indiquer dans quel(s) dossier(s) le suivi des modifications doit être fait.

S'il existe des logiciels fournissant une interface graphique pour gérer le suivi des modifications ([Wikipedia en fournit un comparatif incomplet](https://en.wikipedia.org/wiki/Comparison_of_Git_GUIs)), Git s'utilise à l'origine en ligne de commande. Il existe beaucoup de commandes, mais quelques commandes de base suffisent pour gérer le suivi des modifications au quotidien. Voici quelques exemples.

| commande | fonction |
| :------- | :------- |
| `git init` | commencer le suivi |
| `git add fichier1.md` | ajouter un ou plusieurs fichiers/dossiers au suivi |
| `git commit -am "fichier1.md modifié"` | enregistrer des modifications |
| `git push origin master` | envoyer les modifications locales vers un dépôt distant |
| `git pull origin master` | récupérer les modifications distantes sur son ordinateur |

Git a des fonctions très poussées qui ne sont pas utiles ici. Pour en savoir plus, reportez-vous au livre recommandé dans la bibliographie (Chacon, Straub, 2014) ou à la [documentation officielle](https://git-scm.com/doc).

GitHub, pour sa part, est une plateforme d'hébergement et de gestion de développement, utilisé principalement pour la mise à disposition de logiciel open source. Cette plateforme a contribué à la popularité de Git. C'est un exemple de dépôt distant vers lequel on peut pousser (`git push`) les modifications faites sur son ordinateur.

[GitLab](https://gitlab.com/), plateforme commerciale similaire à GitHub, met à disposition le [code source](https://gitlab.com/gitlab-org/gitlab-ce) de base permettant de créer son propre dépôt Git (ex. [Framagit](https://framagit.org)).

Notez que Git n'est pas le seul système de gestion des versions. Il y a aussi [Subversion](https://subversion.apache.org/) (aussi connu sous le nom de svn), [Mercurial](https://www.mercurial-scm.org/) ou [Bazaar](http://bazaar.canonical.com/), tous trois libres, pour n'en citer que quelques-uns. Contrairement aux autres, Subversion n'est pas un système distribué.