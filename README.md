# Webring Data

Ce repository contient toutes les configs derrières le 
[webring du Nouveau Printemps](https://ring.nouveauprintemps.org).
Le logiciel utilisé derrière est celui 
[créé par le Nouveau Printemps](https://github.com/Nouveau-Printemps/webring).

## Concept

Le Nouveau Printemps est une association de recherche et de construction visant à réflechir sur le
monde.
Nous cherchons à dépasser la barrière idéologique provoquant une analyse rapide, futile et 
subjective pour ouvrir l'horizon des possibles.
Nous construisons un ensemble d'outils pour s'émanciper des sentiers battus pour atteindre une 
véritable souveraigneté individuelle et numérique dans le monde numérique.

Notre objectif est de construire un nouvel idéal combinant respect de la nature, de l'humain et des
libertés.

Ce webring contient tous les membres du Nouveau Printemps possédant un site web.

## Rejoindre le cercle

Pour nous rejoindre, vous devez évidemment adhérer à notre vision du monde profondément humaniste
et animiste.
Nous ne cherchons pas à créer une uniformité dans nos débats : nous voulons juste avancer sur des
valeurs que nous considérons comme justes et rationnelles.

Pour soumettre votre demande, vous devez fork ce repository et vous rajouter à la fin du fichier 
`config.toml`, e.g.
```toml
[[websites]]
  name = "Votre nom"
  url = "https://example.org/"
```

Ensuite, faites une Pull Request en expliquant pourquoi vous souhaitez nous rejoindre.

Une fois que votre demande est acceptée, vous devez ajouter l'image du Nouveau Printemps sur votre
site.
```html
<todo>faire un exemple</todo>
```

Au fois rajouté, votre PR sera merge et vous serez officiellement sur le webring.
