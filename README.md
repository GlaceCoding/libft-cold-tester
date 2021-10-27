# libft-cold-tester
libft Tester version 10/2021

Testeur rapide (car il teste toutes les fonctions en une seule fois dans un fichier test.c). Si vous n'avez pas fini votre projet vous devrez commencer les blocs de tests des fonctions pas encore faites.

Il y a deux façon de rendre strcmp soit avec +1/1/0 ou la différence en byte (+42/42/0).  
Pour le format +1/1/0 enlever le flag `-fno-builtin` dans test.sh pour les raisons expliquées ici : <https://stackoverflow.com/a/54281841/>.

https://github.com/GlaceCoding/libft-cold-tester/blob/72f9ccd98eee2b0fa341d13a3e873a6fc60c9502/test/test.sh#L4

Certain test sont un peu plus sévère que la moulinette car je test que l'allocation de mémoire a été alloué au byte près.

## Usage

Pour utiliser le testeur, mettez le contenu de ce repo dans votre projet ou modifier l'include à libft.h dans test.c.

## Autres testeurs :

 - https://github.com/jtoty/Libftest
 - https://github.com/alelievr/libft-unit-test
 - https://github.com/Tripouille/libftTester
