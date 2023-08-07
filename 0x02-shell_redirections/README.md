0x02-shell_redirections

## Script de Comptage de Répertoires
Ce script compte le nombre de répertoires et sous-répertoires dans le répertoire courant, en incluant les répertoires cachés mais en excluant le répertoire courant et le répertoire parent. Il utilise la commande `ls` pour lister tous les fichiers et répertoires récursivement avec les options -laR, puis utilise `grep` pour filtrer les lignes qui commencent par "d" (indiquant les répertoires) et enfin `grep -c` pour compter le nombre de lignes résultantes. Le script est exactement deux lignes de longueur et est exécutable.

