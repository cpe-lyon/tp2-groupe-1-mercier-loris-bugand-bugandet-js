# TP 2 - Bash
## Exercice 1. Variables d’environnement

**1.**

**2.** La variable **$HOME** contient le chemin absolu vers le répertoire personnel de l'utilisateur connecté.

**3.**
* La variable **$LANG** est utilisée par les différents programmes pour déterminer la langue des messages à afficher. 

**Par exemple :** _`LANG=fr ls fff`_ => _ls: fff: Aucun fichier ou répertoire de ce type_ **|** _`LANG=en ls fff`_ => _ls: fff: No such file or directory_
* La variable **$PWD** contient le chemin absolu vers le répertoire courant (permet de savoir où on est dans l'arborescence).
* La variable **$OLDPWD** contient le chemin absolu vers le répertoire courant précédent (permet de savoir d'où on vient).
* La variable **$SHELL** indique l'interpréteur shell utilisé par défaut. La valeur habituelle sous linux est /bin/bash (plus rarement /bin/sh).
* La variable **$_** contient le dernier argument placé dans la dernière commande shells.

**4.** Pour créer la variable **My_Var** en bash il suffit de taper la commande _`MyVar='la valeur de la variable'`_. Nous pouvons vérifier son existance en utilisant la commande _`echo $My_Var`_.

**5**

**6** 
