# Syntaxe

Les règles de baslisage de Markdown sont peu nombreuses. Dans la version d'origine, il y en a exactement douze (Gruber, 2013).

## paragraphe
Les paragraphes sont séparés par une (ou plusieurs lignes) vide(s).

> et la "règle" des 3 espaces en fin de ligne ?

## titres
Les titres sont précédés d'un à six `#`, suivi d'un espace, selon le niveau du titre:

`#` pour un titre de niveau 1   
`##` pour un titre de niveau 2   
`###` pour un titre de niveau 3   
`####` pour un titre de niveau 4   
`#####` pour un titre de niveau 5   
`######` pour un titre de niveau 6   

Il est aussi possible de produire des titres de niveaux 1 et 2 de la manière suivante:

`Titre de niveau 1`   
`=================`

`Titre de niveau 2`   
`-----------------`

## citation
Les citations doivent être précédées d'un `>`, suivi d'un espace:

> It takes many numbers to get close to the truth.


ANON., 2019. It’s time to talk about ditching statistical significance. In : *Nature*. mars 2019. Vol. 567, n° 7748, p. 283. DOI [10.1038/d41586-019-00874-8](10.1038/d41586-019-00874-8). 

Les citations peuvent être imbriquées les unes dans les autres, si, p. ex. vous citez un document qui en cite un autre.

    syntaxe:
    
    > This is the first level of quoting.
    >
    > > This is nested blockquote.
    >
    > Back to the first level.

résultat:   

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

Notez que la syntaxe ci-dessous produit exactement le même résultat:

    > This is the first level of quoting.
    
    > > This is nested blockquote.
    
    > Back to the first level.


Les citations peuvent contenir, si besoin, des titres, des listes à puces et du code (voir ci-dessous).

> ### This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");

## Liste à puce
Pour créer une liste à puces simple, vous pouvez utiliser des `*`, des `+` ou des `-`. Cela produit exactement le même résultat.

    syntaxe:
    
    * rouge
    * bleu
    * vert

résultat:   

* rouge
* bleu
* vert

Pour créer une liste à puces numérotées, vous ddevez utiliser un chiffre suivi d'un point.

    syntaxe:
    
    1. rouge
    2. bleu
    3. vert

résultat:   

1. rouge
2. bleu
3. vert

Notez que les chiffres n'ont pas d'importance. La liste suivante donne exactement le même résultat que celle présentée ci-dessus:

    syntaxe:
    
    8. rouge
    1. bleu
    4. vert

Finalement, vous pouvez alterner les entéres d'une liste à puces avec des paragraphes ou des citations comme suit:

	syntaxe:
	
	*   Albert Einstein
	
	    > Markdown lets you almost write at the speed of light.
	
	*   Niels Bohr

résultat:

*   Albert Einstein
	
    > Markdown lets you almost write at the speed of light.
	
*   Niels Bohr

### Exercices

Numérotez des années 

1986. What a great season.

1986\. What a great season.

## 
