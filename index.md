---
title: DevOps au quotidien
---

# _12 septembre 2017, seconde entrée :_ [jq l'outil de manipulation de JSON](/2017/09/12/jq.html)

L'usage du JSON est désormais généralisé. A l'image des outils pour traiter du XML en ligne
de commande, de manière scriptable, il existe un excellent outil de manipulation de JSON : `jq`.

# _11 septembre 2017, première entrée :_ [bonjour et bienvenue !](/2017/09/08/bonjour.html)

La création de ce blog est l'occasion de présenter [Github Pages](https://pages.github.com/) que j'ai choisi
d'utiliser, tout en vous souhaitant la bienvenue.

# Mes contributions sur Github

Voici la liste de mes dépôts publiques sur Github. Des tests ; des prototypes balbutiants ; de petits projets ; et ce blog :) 

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
