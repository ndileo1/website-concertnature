# Ananke, A theme for [Hugo](https://gohugo.io/), a framework for building websites


* Récupérer le projet concertnature-website
  - Telecharger VsCode
  - Telecharger Hugo
  - Telecharger Git
  - Cloner le projet Git

* Contruire le site web
  - supprimer le dossier `public`
  - ```hugo --minify --buildFuture``` 
  attention ne pas utiliser `hugo server --minify --buildFuture`
  
* Publier le site web
  - se connecter au server via FileZilla (voir note dans dossier info/s)
  - Supprimer le contenu de `/`
  - Téléverser le contenu du dossier `/public` vers le site distant 
  (attention la taille du dossier `/public` ne doit pas dépasser 10Mb, a voir si on augmente la taille sur Infomaniac)


