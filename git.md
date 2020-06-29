# GIT

## Initialiser le projet

Dans un terminal à la racine du projet :

```bash
git init
```

## Commit & push

Toujours dans le terminal à la racine du projet :

```bash
git add .
git commit -m "nom du commit"
git remote add origin git@github.com:username/repo_name.git
git push -u origin master
```

## Branch

Toujours dans le terminal au même endroit :

```bash
git checkout -b "nom de la branche"