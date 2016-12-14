---
title: Retour sur Jekyll !
layout: post
date: '2016-12-11 06:57:17 +0100'
categories: jekyll update
---

L'hiver arrive, temps de reprendre les explorations et [quelques engagements indieweb](https://indieweb.org/2017-01-01-commitments) où j'aimerais m'engager publiquement pour implémenter de nouvelles fonctionnalités sur mon site personnel.

Après maintes explorations passionnantes et difficiles [démarrées en 2013](https://christopheducamp.com/2013/12/03/premier-pas-sur-jekyll/) pour découvrir GitHub et les fondamentaux des générateurs statiques, je suis très heureux de repartir sur cette nouvelle branche (de sous-domaine de famille) afin d'apprendre, tester les nouvelles fonctionnalités de Jekyll découvertes via la [communauté jekyll francophone](http://jekyll-fr.org/) et aider quelques amis qui voudraient se lancer en 2017. 

Plein de manières de reconstruire le site, mais je commencerai par la plus commune, à savoir lancer `bundle exec jekyll serve` dans la fenêtre de Terminal, afin de lancer un serveur et autorégénérer le site à chaque fois qu'un fichier est mis à jour.

## Ajout de nouveaux posts 

Pour ajouter de nouveaux posts, et faute de disposer nativement du plugin `[jekyll-admin](https://github.com/jekyll/jekyll-admin)`, je prévois d'utiliser la méthode rustique. Ajout d'un fichier dans le répertoire `_posts` en suivant la convention `AAAA-MM-JJ-nom-du-post.ext` et contient le front matter nécessaire.

{% highlight yml %}
---
layout: post
title:  "Retour sur Jekyll !"
date:   2016-12-11 06:57:17 +0100
categories: jekyll update indieweb
---
{% endhighlight yml %}

Jekyll offre aussi un support puissant des fragments de code : 

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Pour plus d'informations, regarder la [doc de Jekyll docs][jekyll-docs]. Si vous avez des questions, vous pouvez les poser sur  [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

## Prochaines étapes

1.  Valider cette branche avec https://indiewebify.me/... 
2.  Localiser la date en français

## Source 

[Editez directement le contenu](https://github.com/ChristopheDucamp/christopheducamp.github.io)