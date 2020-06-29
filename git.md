# GIT

## Creer le repos sur github

![new repo github](./create_new_repo.png)

Après ça, on tombe sur cette page que l'on garde de côté pour trouver les 2 ligne de commande après le commit pour 1er push

![commande](./info_command.png)

## Initialiser le projet

Dans un terminal à la racine du projet :

```bash
git init
```

-> initialise git dans le dossier

![git init](./git_init.png)

## Commit & push

Toujours dans le terminal à la racine du projet :

```bash
git add .
git commit -m "nom du commit"
git remote add origin git@github.com:username/repo_name.git
git push -u origin master
```

![commit](./commit_push_first.png)

-> permet de faire le 1er commit push ensuite on fera simplement:

```bash
git add .
git commit -m "nom 0du commit"
git push
```

## Branch

Toujours dans le terminal au même endroit :

```bash
git checkout -b "nom de la branche"
```

-> permet de créer et de bascler sur la nouvelle branche.
