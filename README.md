# Terminal 101

## Chemins

- . : fait référence au dossier dans lequel on se trouve
- ./: fait référence au dossier dans lequel on se trouve

- .. : fait référence au dossier parent
- ../ : fait référence au dossier parent

- ~ : représente la racine des dossiers personnels
  - linux: /home/[nom_utilisateur]
  - mac: /Users/[nom_utilisateur]
  - windows: C:\Utilisateurs\[nom_utilisateur]

on peut se déplacer en utilisant soit un chemin relatif à la ou on se trouve ou un chemin absolu (à partir de la racine de l'ordinateur)

> exemples

- relatif:

```bash
$ cd cours/dw12
#################################
$ cd ./cours/dw12
```

- absolu

```bash
$ cd /home/david/cours/dw12
```

pour revenir sur au dossier précédent on peut utiliser cd -

```bash
# on se déplace dans le dossier /home/cours/tmp
$ cd /home/cours/tmp
# on change de dossier pour le dossier racine /
$ cd /
# en utilisant cd - on se retrouvera dans le dossier /home/cours/tmp
$ cd -
```

## Commandes Unix (linux/mac)

## sudo

super user do (permet d'accorder les privilèges super utilisateur (admin))

```bash
$ sudo apt install php
```

## clear

nettoie le terminal

```bash
$ clear
```

## touch

```bash
$ touch <nom_du_fichier_a_creer>
```

> exemple

```bash
$ touch index.html
```

## cd

change directory (permet de changer de dossier/repertoire)

```bash
# valeur par défaut: dossier personnel
$ cd [chemin_du_dossier]
```

> exemples

```bash
$ cd Documents
```

```bash
# pour remonter d'un niveau dans l'arborescence (dossier parent)
$ cd ..
# ou
$ cd ../
```

```bash
# pour remonter de 2 niveaux (parent du dossier parent)
$ cd ../..
# ou
$ cd ../../
```

## ls

list (permet de lister le contenu d'un dossier)

```bash
# valeur par défaut: . (dossier dans lequel on se trouve)
$ ls [chemin_du_dossier_a_lister]
```

> exemples

```bash
# va lister le dossier dans lequel on se trouve
$ ls
```

- options

  - ls -l : liste avec plus de details
  - ls -a : affiche aussi les fichiers cachés
  - ls -la: liste avec plus de details et affiche aussi les fichiers cachés

## man

permet de voir le manuel pour une commande

```bash
$ man <command>
```

> exemple

```bash
$ man ls
```

## rm

supprime un fichier

```bash
# la commande rm attends le chemin vers un ou des fichiers
$ rm <chemin_vers_le_fichier>
```

> exemples

```bash
# ici le fichier index.html se trouve dans le meme dossier
$ rm index.html
# ici le fichier index.html se trouve dans un autre dossier que celui dans lequel on se trouve
$ rm cours/tmp/index.html
# on peut supprimer plusieurs fichier en même temps
$ rm index.js /home/david/test.txt
```

- options

  - rm -r : supprime un dossier et son contenu
  - rm -i : supprime de manière interactive (demande pour chaque suppression)
  - rm -f : supprime un fichier en forçant la suppression
  - rm -v : donne un feedback (retour) lors de la suppression
  - rm -rf : supprime un dossier et son contenu en forçant la suppression
  - rmdir : supprime un dossier vide

## mkdir

make directory (permet de créer un ou des dossiers)

```bash
$ mkdir <nom_de_dossier>
```

- options

  - mkdir -p : permet de créer un dossier et de créer les dossiers intermédiaires s'ils n'existent pas

```bash
# va créer le dossier images et le dossier html et le dossier cours s'ils n'existent pas
$ mkdir -p cours/html/images
```

## pwd

print working directory (affiche le chemin absolu jusqu'a l'endroit ou on se trouve)

```bash
$ pwd
```

## cat

concatenate (si un seul nom de fichier est spécifié, la commande affichera le contenu du fichier)

```bash
# va afficher le contenu du fichier sur la sortie standard
$ cat <chemin_vers_le_fichier>
```

> exemples

```bash
# va afficher le contenu du fichier sur la sortie standard
$ cat index.html
```

- less : similaire à cat mais permet de "naviguer" dans le fichier
- more : similaire à less

## mv

move

```bash
# renommer
$ mv mon-fichier-a-renommer.txt mon-fichier-renome.txt
# déplacer
$ mv mon-fichier-a-renommer.txt mon-dossier/
# déplacer
$ mv mon-fichier-a-renommer.txt mon-dossier/mon-dossier-2/encore-un-autre
# déplacer et renommer
$ mv mon-fichier-a-renommer.txt mon-dossier/mon-dossier-2/fichier.md
```

##

## Raccourci clavier pour le terminal

https://blog.ssdnodes.com/blog/cheatsheet-bash-shortcuts/
