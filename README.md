- . : fait référence au dossier dans lequel on se trouve
- .. : fait référence au dossier parent

- sudo : super user do (permet d'accorder les privilèges super utilisateur (admin))

- cd : change directory (permet de changer de dossier/repertoire)

  - ex: cd Documents
  - ex: cd ../ (pour remonter d'un niveau dans l'arborescence)
  - ex: cd ../../ (pour remonter de 2 niveaux)

- ls : list (permet de lister le contenu d'un dossier)
  - ex: ls (va lister le contenu du dossier dans lequel on se trouve)
- ls -l : liste avec plus de details
- ls -a : affiche aussi les fichiers cachés
- ls -la: liste avec plus de details et affiche aussi mles fichiers cachés

- man <command>: permet de voir le manuel pour une commande

- rm : supprime un fichier
- rm -r : supprime un dossier et son contenu
- rmdir : supprime un dossier vide
- rm -f :supprime un fichier en forçant la suppression
- rm -rf : supprime un dossier et son contenu en forçant la suppression

- mkdir [nom_de_dossier...] : make directory (permet de créer un ou des dossiers)
- mkdir -p : permet de créer un dossier et de créer les dossiers intermédiaires s'ils n'existent pas

  - ex: mkdir -p cours/html/images (va créer le dossier images et le dossier html et le dossier cours s'ils n'existent pas)

- pwd : print working directory (affiche le chemin absolu jusqu'a l'endroit ou on se trouve)

- cat : concatenate (si un seul nom de fichier est spécifié, la commande affichera le contenu du fichier)
- less : similaire à cat mais permet de "naviguer" dans le fichier
- more : similaire à less

- mv : move
  - pour renommer ex : mv mon-fichier-a-renommer.txt mon-fichier-renome.txt
  - pour deplacer ex : mv mon-fichier-a-renommer.txt mon-dossier/
  - pour deplacer ex : mv mon-fichier-a-renommer.txt mon-dossier/mon-dossier-2/encore-un-autre
  - pour deplacer et renommer ex : mv mon-fichier-a-renommer.txt mon-dossier/fichier.txt
  - pour deplacer et renommer ex : mv mon-fichier-a-renommer.txt mon-dossier/mon-dossier-2/fichier.md

## Raccourci clavier pour le terminal

https://blog.ssdnodes.com/blog/cheatsheet-bash-shortcuts/
