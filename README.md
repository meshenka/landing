# Landing

Un gabarit de landing page de démo sous Jekyll

Pour le gabarit voir http://blog.kissmetrics.com/landing-page-design-infographic/?wide=1

## Structure
Pour monter ce gabarit on utilise 3 catégories de posts
  - headline pour le bloc haut - droite: le texte de headline
  - slide pour le bloc haut - gauche pour monter une image ou un slideshow, ou dans le cas présent 2 videos youtube
  - pane, avec le tag [testimony|more] pour gérér les deux blocs image + texte du bas

 Chaque zone du gabarit vas avoir sa template include

 le tout est donc au format site page unique.


## technique

On utilise une instance jekyll standard, le plugin debug est juste la pour la mise au point

Les composants css/js sont pour l'instant inclus via CDN, mais ils seront plus tards inclus via bower

Grunt est la pour tester son utilisation