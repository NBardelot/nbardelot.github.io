Bonjour, et bienvenue sur le code source de ce blog ami lecteur.

Ce README.md correspond au blog [DevOps au quotidien](https://blog.bardelot.fr/),
et il accompagne le code source de ce blog. Si toi aussi tu souhaites mettre en place un blog technique, 
voici une petite recette rapide !

Les étapes principales sont assez simple. Une fois inscrit sur Github avec le compte `username` :
 
   1. il faut créer un projet avec le nom `username.github.io`
      où `username` est donc ton login Github (attention : la casse n'a pas d'importance, mais
      les caractères spéciaux peuvent en avoir...) ;
   2. il faut ensuite aller dans les préférences de ton nouveau projet 
      pour en faire un projet de type *Github Pages* (attention à ne pas confondre avec les préférences
       globales de ton compte) ;
   3. enfin, il faut créer les premiers fichiers nécessaires dans ton projet,
      qui vont servir au préprocesseur Jekyll qu'utilise *Github Pages* pour 
      transformer le markdown que tu commit en HTML à présenter à tes lecteurs.
      
Une bonne option pour commencer, c'est de tout simplement forker mon projet :)

Voici quelques liens utiles pour débuter :
  * une [cheatsheet markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
  * la documentation de [Jekyll](https://jekyllrb.com/)
     * en particulier, le fichier de configuration [_config.yml](https://jekyllrb.com/docs/configuration/)
     * comment organiser l'[arborescence](https://jekyllrb.com/docs/structure/)
     * les options de [formatage des pages](https://jekyllrb.com/docs/frontmatter/)

Et enfin, si tu possèdes un nom de domaine, tu peux également demander à Github
de déclarer un reverse DNS sur le domaine ou sous-domaine de ton
choix en allant dans les propriété du projet *Github Pages*.
 
Bon courage à toi aussi dans tes aventures !