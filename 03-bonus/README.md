# Bonus

## Transposer

En vue d'une formation, il y a souvent un **support de cours** et un **support de présentation** à préparer. Le premier est prévu pour être distribué aux participants, le second à être projeter pendant la formation.

Il arrive que les *slides* projetées servent de support de cours avec l'inconvénient que cela n'est pas toujours adapté à la prise de note et que cela pousse à tout écrire sur les *slides*... :-(

Markdown offre l'avantage de pouvoir transformer le support de cours en *slides* assez facilement et rapidement. Il faut par contre être conscient qu'un certain nombre de fioritures ne pourront pas être intégrées aux *slides* et qu'elles auront un style plutôt épuré. Le style dépend de la plateforme utilisée. En voici deux dont une version libre et auto-hébergeable:

* [HackMD](https://hackmd.io), dont la version libre et auto-hébergeable s'appelle [CodiMD](https://github.com/hackmdio/codimd)
* [slides.com](https://slides.com/), basé sur [reveal.js](https://github.com/hakimel/reveal.js)

Notez que HackMD est aussi basé sur reveal.js, ce qui implique que la création de slides se fait de la même manière sur ces deux plateformes, par l'ajout de `---` ou de `----` précédés et suivis d'une ligne vide.

## Convertir

Vous pouvez aussi convertir des fichiers Markdown dans d'autres formats sans utiliser GitBook. [**Pandoc**](https://pandoc.org) peut le faire de pratiquement n'importe quel format vers pratiquement n'importe quel autre format. Pour en savoir plus sur ce couteau suisse en ligne de commande, je vous recommande un article (Bonjour, 2013) ou la [documentation officielle](https://pandoc.org/MANUAL.html).
