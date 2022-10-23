**Compte rendu TP 2 Bash**

**<ins>Exercice 1. Variables d'environnement</ins>**

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
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image7.png)
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
> 
> Ajout du chemin pour les scripts dans le PATH :
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image11.png)
>
> **<ins>Exercice 2. Contrôle de mot de passe</ins>**
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image12.png)
>
> **<ins>Exercice 3. Expressions rationnelles</ins>**
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image13.png)
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image14.png)
>
> **<ins>Exercice 4. Contrôle d'utilisateur</ins>**
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image15.png)
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image16.png)
>
> **<ins>Exercice 5. Factorielle</ins>**
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image17.png)
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image18.png)
>
> **<ins>Exercice 6. Le juste prix</ins>**
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image19.png)
>
> ![](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image20.png)
>
> **<ins>Exercice 7. Statistiques</ins>**
>
> ![Une image contenant texte Description générée
> automatiquement](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image21.png)
>
> ![Une image contenant texte Description générée
> automatiquement](vertopal_27af89dc06304f3292fb7fc711cdd886/media/image22.png)

Elements de correction:

Version sans test des paramètres:

![image](https://user-images.githubusercontent.com/104362418/197400688-44e20804-ef94-494b-bbec-3d23ac37b5d6.png)

Test des paramètres : 

![image](https://user-images.githubusercontent.com/104362418/197400727-f374db6a-6676-42da-8e4b-dbf008e3d993.png)

![image](https://user-images.githubusercontent.com/104362418/197400734-4bdc5728-3052-4360-a65c-9c554eb57bcf.png)

Avec plus ou moins de 3 paramètres :

![image](https://user-images.githubusercontent.com/104362418/197400781-564e9276-ae1e-4199-95ed-6cca0474a4a5.png)

![image](https://user-images.githubusercontent.com/104362418/197400789-0175dc72-732f-4d0f-97e9-40a4fc0f80da.png)

![image](https://user-images.githubusercontent.com/104362418/197400799-a79f85e6-d3c3-4d5c-b5f5-43b840d7f9b5.png)

Solution complète:

![image](https://user-images.githubusercontent.com/104362418/197400835-000c19ea-e7bd-4dd2-af7e-df54d499471a.png)

Quelques petites aides:

![image](https://user-images.githubusercontent.com/104362418/197330981-92014b92-0a64-40aa-b890-1032e0cf62f1.png)

![image](https://user-images.githubusercontent.com/104362418/197330986-5a092378-a567-4ea4-bd56-844f24eac6b9.png)

