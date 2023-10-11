# Ars Chronica
Jeu médiéval, historique et fantastique

Site accessible sur  https://guillaume-alvarez.github.io/ars-chronica/ 

## Build

Builder le site en local:
```
hugo server -D -E -F --port 8080 --bind 0.0.0.0 --renderToDisk
```

Le site est sur la branche gh-pages, buildé avec une Github Action, configurée par le fichier `.github/workflows/hugo.yaml` de https://gohugo.io/hosting-and-deployment/hosting-on-github/
