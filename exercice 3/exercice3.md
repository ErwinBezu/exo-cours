Créer un nouveau repository Git

```
git init
```

Ajouter un fichier et le commiter (C1)

```
git add .
git commit -m "C1"
```

Modifier la première ligne du fichier et commiter (C2)

```
git add .
git commit -m "C2"
```

Créer une feature branch B1 à partir de C1

```
git log
git checkout -b B1 13dbe6673766df9e7bf36d142baac07cf1737aef

```

Faire une modification de la première ligne du fichier et commiter (C3)

```
git add .
git commit -m "C3"
```

Merger B1 dans main ou master en résolvant les conflits

```
git checkout main
git merge B1

```

![alt text](image.png)
