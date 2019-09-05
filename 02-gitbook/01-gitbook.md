## GitBook

![](../img/gitbook.svg)

Nous avons déjà vu ce qu'est GitBook, il faut encore savoir qu'il se décline sous 3 formes:

1. une plateforme commerciale ([https://gitbook.com](https://gitbook.com))
2. une plateforme auto-hébergeable ([https://github.com/GitbookIO/gitbook](https://github.com/GitbookIO/gitbook))
3. un logiciel ([https://legacy.gitbook.com/editor](https://legacy.gitbook.com/editor))

Dans les 2 premiers cas, la marche à suivre prévue est la suivante :

1. rédaction en Markdown (sur son ordinateur)
2. enregistrement et envoi des modifications sur une plateforme distante (avec Git)
3. conversion automatique des fichiers Markdown (par la plateforme)

Le lien entre le dépôt Git (étape 2) et la plateforme GitBook (étape 3) doit être configuré.

Dans le cas du logiciel, tout se fait directement dans son interface.


### plateforme commerciale

GitBook est d'abord une plateforme en ligne de publication de documentation basée sur Git et Markdown. L'idée est de permettre à l'utilisateur de rédiger en Markdown et de publier un document sans devoir s'occuper de la mise en forme.

La version originale de la plateforme ([https://legacy.gitbook.com](https://legacy.gitbook.com)) permet de convertir le document en PDF, ePub, Mobi ou HTML.
La version 2 ne permet plus de faire cela! Le contenu est donc seulement disponible en ligne en HTML.


### plateforme auto-hébergeable

Le code source fourni par les développeurs de GitBook permet d'héberger soi-même une instance de GitBook (ex. [https://docs.framasoft.org](https://docs.framasoft.org)).


### logiciel

GitBook Editor est un logiciel, pour GNU/Linux, Mac OSX et Windows, fournissant une interface graphique pour suivre et enregistrer les modifications, et mettre à jour les documents ainsi créés, sans passer par la ligne de commande.
L'inconvénient de ce logiciel est qu'il ne fonctionne qu'avec la plateforme gitbook.com et pas une version auto-hébergée.


---

### Notes personnelles
