# raspberry addventure

## instructions

Pour démarrer votre aventure :

```sh
$ mkdir mon-prenom # créer un dossier qui porte votre nom
$ cp intro.txt mon-prenom/aventure.txt # créer une copie du fichier de base dans ce dossier
$ nano mon-prenom/aventure.txt # ecrire dans le fichier
```

Pour ajouter vos modifications au dépôt git

```sh
$ git add . # ajouter toutes les modifications
$ git commit -m "explication des modifications"
$ git pull # synchroniser avec le dépôt distant
$ git push # uploader les modifications
```

Pour continuer les aventures de vos camarades :

```sh
$ git pull origin main # mettre à jour depuis le dépôt git
$ nano prenom-camarade/aventure.txt
```

Faire lire son texte par l'ordinateur (sur macOS) :

```sh
$ cat intro.txt | say -v Thomas
```

## cheatsheet

(cf. [Peer-to-Peer-Folder-Poetry](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/code-societies-2020.md))

| Command                                    | Description                                   |
| ------------------------------------------ | --------------------------------------------- |
| `cd`                                       | change directory                              |
| `cd ..`                                    | change directory one level back               |
| `ls`                                       | list contents of directory                    |
| `pwd`                                      | print working directory                       |
| `mkdir foldername`                         | create a folder named "foldername".           |
| `touch dandelion.txt`                      | create a file named dandelion.txt             |
| `echo "woof woof" > kitty.txt`             | creates a text file called kitty.txt that contains the words, "woof woof"|
| `cat filename.txt`                         | print contents of file                        |
| `rm filename.txt`                          | remove a file                                 |
| `rm -r folder`                             | remove a folder                               |
| `mv filename.txt newfilename.txt`          | rename a file                                 |
| `cp filename.txt filename2.txt`            | copy file                                     |
| `man cd`                                   | show the manual for 'cd'. Press q to quit     |
| `source ~/.bash_profile`                   | restart your terminal config file             |


### resources

* [shell initiation](https://github.com/patriciogonzalezvivo/Shell-Initiation)
* [shell](https://www.fjamet.com/technologies/tangible/raspberry/shell.html)


### crédits

La phrase d'introduction

> Il était en train de passer l'aspirateur quand le téléphone sonna.

est un incipit du nouvelliste Raymond Carver.