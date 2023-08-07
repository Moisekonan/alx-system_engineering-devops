0x02-shell_redirections

## Script de Comptage de Répertoires
Ce script compte le nombre de répertoires et sous-répertoires dans le répertoire courant, en incluant les répertoires cachés mais en excluant le répertoire courant et le répertoire parent. Il utilise la commande `ls` pour lister tous les fichiers et répertoires récursivement avec les options -laR, puis utilise `grep` pour filtrer les lignes qui commencent par "d" (indiquant les répertoires) et enfin `grep -c` pour compter le nombre de lignes résultantes. Le script est exactement deux lignes de longueur et est exécutable.

## Script de Suppression de Caractères
Ce script supprime toutes les lettres c et C de l'entrée. Il utilise la commande `tr` avec l'option `-d` pour effectuer la suppression. Le script est exactement deux lignes de longueur et est exécutable.

## Script d'Inversion d'Entrée
Ce script inverse son entrée en utilisant la commande `rev`. Le script est exactement deux lignes de longueur et est exécutable.


## Script de Remplacement de Caractères
Ce script remplace tous les caractères A et c de l'entrée par Z et e respectivement. Il utilise la commande `tr` pour effectuer le remplacement. Le script est exactement deux lignes de longueur et est exécutable.
