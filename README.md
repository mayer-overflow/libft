
# Libft
La Librairie C standard, ainsi qu'un certain nombre de fonctions additionnelles.

**installation**
1. `git clone https://github.com/mayer-overflow/libft.git` 
2. `cd libft`
3. `make`
4. Enjoy my `libft.a`

## Partie 1
Consulter le `man` ou `info` pour le détail des fonctions suivantes

* ft_atoi.c
* ft_bzero.c
* ft_foreach.c
* ft_isalnum.c
* ft_isalpha.c
* ft_isascii.c
* ft_isdigit.c
* ft_isprint.c
* ft_lstadd.c
* ft_lstdel.c
* ft_lstdelone.c
* ft_lstiter.c
* ft_lstmap.c
* ft_lstnew.c
* ft_memccpy.c
* ft_memchr.c
* ft_memcmp.c
* ft_memcpy.c
* ft_memmove.c
* ft_memset.c
* ft_strcat.c
* ft_strchr.c
* ft_strcmp.c
* ft_strcpy.c
* ft_strdup.c
* ft_strlcat.c
* ft_strlen.c
* ft_strncat.c
* ft_strncmp.c
* ft_strncpy.c
* ft_strnstr.c
* ft_strrchr.c
* ft_strstr.c
* ft_tolower.c
* ft_toupper.c

## Partie 2 (DLC)
**ft_memalloc**
> Alloue avec `malloc(3)` et retourne une zone de memoire "fraiche". La memoire allouee est intialisee a 0. Si l'allocation echoue, la fonction renvoie `NULL`.

**ft_memdel**
> Prend en parametre l’adresse d’un pointeur dont la zone pointee doit etre liberee avec `free(3)`, puis le pointeur est mis a `NULL`.

**ft_strnew**
> Alloue avec `malloc(3)` et retourne une chaine de caractere “fraiche” terminee par un `’\0’`. Chaque caractere de la chaine est initialise a `’\0’`. Si l’allocation echoue, la fonction renvoie `NULL`.

**ft_strdel**
> Prend en parametre l’adresse d’une chaine de caracteres qui doit etre liberee avec `free(3)` et son pointeur mis a `NULL`.

**ft_strclr**
> Assigne la valeur `’\0’` a tous les caracteres de la chaine passee en parametre.

**ft_striter**
> Applique la fonction `f` a chaque caractere de la chaine de caracteres passee en parametre. Chaque caractere est passe par adresse a la fonction `f` afin de pouvoir être modifie si necessaire.

**ft_striteri**
> Applique la fonction `f` a chaque caractere de la chaine de caracteres passee en parametre en precisant son index en premier argument. Chaque caractere est passe par adresse a la fonction `f` afin de pouvoir etre modifie si necessaire.

**ft_strmap**
> Applique la fonction `f` a chaque caractere de la chaine de caracteres passee en parametre pour creer une nouvelle chaine “fraiche” avec `malloc(3)` resultant des applications successives de `f`.

**ft_strmapi**
> Applique la fonction `f` a chaque caractere de la chaine de caracteres passee en parametre en precisant son index pour creer une nouvelle chaine “fraiche” avec `malloc(3)` resultant des applications successives de `f`.

**ft_strequ**
> Compare lexicographiquement s1 et s2. Si les deux chaines sont egales, la fonction retourne 1, ou 0 sinon.

**ft_strnequ**
> Compare lexicographiquement s1 et s2 jusqu’a n caracteres maximum ou bien qu’un `’\0’` ait ete rencontre. Si les deux chaines sont egales, la fonction retourne 1, ou 0 sinon.

**ft_strsub**
> Alloue avec `malloc(3)` et retourne la copie "fraiche" d'un troncon de la chaine de caracteres passee en parametre. Le troncon commence a l'index `start` et a pour longueur `len`. Si `start` et `len` ne designent pas un troncon de chaine valide, le comportement est indetermine. Si l'allocation echoue, la fonction renvoie `NULL`.

**ft_strjoin**
> Alloue avec `malloc(3)` et retourne une chaine de caracteres "fraiche" terminee pas un `'\0'` resultant de la concatenation de `s1` et `s2`. Si l'allocation echoue, la fonction renvoie `NULL`.

**ft_strtrim**
> Alloue avec `malloc(3)` et retourne une copie de la chaine passee en parametre sans les espaces blancs au debut et a la fin de cette chaine. On considere comme des espaces blancs les caracteres `' '`, `'\n'` et `'\t'`. Si `s` ne contient pas d'espaces blancs au debut ou a la fin, la fonction renvoie une copie de `s`. Si l'allocation echoue, la fonction renvoie `NULL`.

**ft_strsplit**
> Alloue avec `malloc(3)` et retourne un tableau de chaines de caracteres "fraiches" (toutes terminees par un `'\0'`, le tableau egalement donc) resultant de la decoupe de `s` selon le caractere `c`. Si l'allocation echoue, la fonction retourne `NULL`.

**ft_itoa**
> Alloue avec `malloc(3)` et retourne une chaine de caracteres "fraiche" terminee par un `'\0'` representatnt l'entier `n` passe en parametre. Les nombres negatifs sont geres. Si l'allocation echoue, la fonction renvoie `NULL`.

**ft_putchar**
> Affiche le caractere `c` sur la sortie standard.

**ft_putstr**
> Affiche la chaine `s` sur la sortir standard.

**ft_putendl**
> Affiche la chaine `s` sur la sortie standard suivi d'un `'\n'`.

**ft_putnbr**
> Affiche l'entier `n` sur la sortie standard.

**ft_putchar_fd**
> Ecrit le caractere `c` sur le descripteur de fichier `fd`.

**ft_putstr_fd**
> Ecrit la chaine `s` sur le descripteur de fichier `fd`.

**ft_putendl_fd**
> Ecrit la chaine `s` sur le descripteur de fichier `fd` suivi d'un `'\n'`.

**ft_putnbr_fd**
> Ecrit l'entier `n` sur le descripteur de fichier `fd`.


## Fonctions bonus

**ft_range.c**
> Prend en parametre deux entier `min` et `max` et retourne un tableau alloue en memoire, contenant l'ensemble des entiers qui les separent.

**ft_sqrt.c**
> Prend en parametre un entier `nb` et retourne sa racine si elle existe. Sinon, la fonction retourne `0`

**ft_str_reverse.c**
> inverse la chaine de caracteres `s` passé en parametre.

**ft_swap.c**
> Prend en parametre deux pointeurs sur entier, `a` `b` et echange leur valeurs.


**ft_islower.c**

**ft_isupper.c**

**ft_putendl_nb.c**

**ft_putstr_nbr.c**

**ft_recursive_factorial.c**

**ft_tobinary.c**






