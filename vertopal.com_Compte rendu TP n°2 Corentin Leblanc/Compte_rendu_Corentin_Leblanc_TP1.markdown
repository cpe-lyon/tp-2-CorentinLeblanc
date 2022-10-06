**[Compte rendu TP 2 Bash]**

**[Exercice 1. Variables d'environnement]**

1 -- Bash trouve les commandes tapées par l'utilisateur dans les
dossiers présents dans le PATH.

2 -- C'est la variable d'environnement nommée PWD (Path Work Directory)
qui permet à la commande cd de nous ramener dans le répertoire personnel
lorsqu'elle est renseigné sans argument

3 -- Le rôle des variables suivantes est de :

-   LANG : défini la langue du système d'exploitation (exemple :
    en_US.UTF-8)

-   PWD : défini le chemin du répertoire personnel (exemple :
    /home/corentin)

-   OLDPWD : défini l'ancien chemin du répertoire personnel

-   SHELL : défini le système d'exploitation sur lequel on se trouve

> 4 -- J'ai créé une variable locale nommée MY_VAR et vérifié qu'elle
> existe bien.
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image1.png)
>
> 5 -- La commande « bash » supprime les variables locales. La variable
> « MY_VAR » n'apparaît par conséquent plus lorsque je demande à
> l'afficher.
>
> ![Une image contenant texte Description générée
> automatiquement](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image2.png)
> 6 -- Après avoir créer une variable d'environnement cette fois-ci. Je
> constate donc qu'après avoir fait la commande « bash », la variable
> d'environnement est encore présente comparé à la variable locale. Ceci
> s'explique par le fait que la variable locale est uniquement pour la
> session en cours, la variable d'environnement est quand à elle globale
> et peut modifier le comportement de certains programmes.
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image3.png)
>
> 7 -- Je me suis servis des commandes du cours pour créer une nouvelle
> variable d'environnement
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image4.png)
>
> 8 -- Voici les commandes que j'ai utilisé pour faire afficher la
> phrase « Bonjour à vous, Corentin Leblanc ! »
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image5.png)
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image6.png)
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image7.png
>
> 9 -- La différence qu'il va y avoir entre donner une valeur vide à une
> variable d'environnement où l'utilisation de la commande « unset » est
> que la commande « unset » va réellement supprimer la variable alors
> que si une variable vide est créée elle sera quand même visible alors
> qu'il n'y a rien dedans.
>
> 10 - Voici les commandes que j'ai renseigné pour faire afficher la
> phrase « \$HOME = chemin »
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image8.png)
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image9.png)
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image10.png)
> Ajout du chemin pour les scripts dans le PATH :
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image11.png)
>
> **[Exercice 2. Contrôle de mot de passe]**
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image12.png)
>
> **[Exercice 3. Expressions rationnelles]**
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image13.png)
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image14.png)
>
> **[Exercice 4. Contrôle d'utilisateur]**
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image15.png)
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image16.png)
>
> **[Exercice 5. Factorielle]**
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image17.png)
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image18.png)
>
> **[Exercice 6. Le juste prix]**
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image19.png)
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image20.png)
>
> **[Exercice 7. Statistiques]**
>
> ![Une image contenant texte Description générée
> automatiquement](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image21.png)
>
> ![Une image contenant texte Description générée
> automatiquement](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image22.png)
