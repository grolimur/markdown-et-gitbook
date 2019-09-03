## GitBook

![](../img/gitbook.svg)

GitBook se décline sous 3 formes:

A. une plateforme commerciale
B. une plateforme auto-hébergeable
C. un logiciel

Dans les 2 premiers cas, la marche à suivre prévue est la suivante :

1. rédaction en Markdown (sur son ordinateur)
2. enregistrement et envoi des modifications sur une plateforme distante (avec Git)
3. conversion automatique des fichiers Markdown (par la plateforme)

Le lien entre le dépôt Git (étape 2) et la plateforme GitBook (étape 3) doit être configuré.

Dans le 3e cas, tout se fait dans l'interface du logiciel.


### plateforme commerciale

GitBook est d'abord une plateforme de publication de documentation, disponible sur [https://www.gitbook.com](https://www.gitbook.com), basée sur Git et Mardkown. L'idée est de permettre à l'utilisateur de rédiger en Markdown et de publier un document sans devoir s'occuper de la mise en forme.

La version originale de la plateforme ([https://legacy.gitbook.com](https://legacy.gitbook.com)) permet de convertir le document en PDF, ePub, mobi ou HTML soit faite pour lui.
La version 2 ne permet plus de faire cela! Le contenu est donc seulement disponible en ligne en HTML.


### plateforme auto-hébergeable

Le code source fourni par les développeurs de GitBook permet d'héberger soi-même une instance de GitBook (ex. [https://docs.framasoft.org](https://docs.framasoft.org)).


### logiciel

GitBook Editor est un logiciel, pour GNU/Linux, Mac OSX et Windows, fournissant une interface graphique pour suivre et enregistrer les modifications, et mettre à jour les documents ainsi créés, sans passer par la ligne de commande.
L'inconvénient de ce logiciel est qu'il ne fonctionne qu'avec la plateforme gitbook.com et pas une version auto-hébergée.


---

Le dépôt GitHub indique que la version auto-hébergeable ne fait plus l'objet d'un développement actif, mais fonctionne toujours.

> As the efforts of the GitBook team are focused on the GitBook.com platform, the CLI is no longer under active development.
> All content supported by the CLI are mostly supported by our GitBook.com / GitHub integration.
Content hosted on the legacy.gitbook.com will continue working until further notice. For differences with the new vesion, check out our documentation.
