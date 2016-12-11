---
layout: post
title:  "Bienvenue sur Jekyll!"
date:   2016-12-11 06:57:17 +0100
categories: jekyll update
---
Nouvelle voie pour tester les nouvelles fonctionnalités de Jekyll découvertes via la communauté jamstatic-fr. Plein de manières de reconstruire le site, mais je commencerai par la plus commune, à savoir lancer `jekyll serve` dans la fenêtre de Terminal, afin de lancer un serveur et autorégénérer le site à chaque fois qu'un fichier est mis à jour.

Pour ajouter de nouveaux post, ajouter simplement un fichier dans le répertoire `_posts` qui suit la convention `AAAA-MM-JJ-nom-du-post.ext` et contient le front matter nécessaire.

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
