<h1>Workshop WordPress</h1>

<p align=center>
<img src="https://img.shields.io/badge/Wordpress-21759B?style=for-the-badge&logo=wordpress&logoColor=white">
</p>

1. Introduction
2. Installation
3. Réglages
4. Thèmes
5. Plugin
6. Création de plugin

# 0. Introduction

Dans ce repository, nous allons vous expliquer comment lancer son premier site WordPress. Vous allez aussi voir des conseils pour avoir des bons régles.
Vous allez apprendre aussi comment installer un plugin et un thème pour votre site.


# 1. Installation et Premier site

- Aller sur www.wordpress.org
  
- Cliquer sur Get Wordpress
  ![image](Images/image1.png)

- Décompresser le dossier wordpress

- Garder le dossier WordPress a un endroit accessible (Il sera utile par la suite)

- Vous avez besoin d'un serveur local (ex: MAMP, WAMP, XAMP,..)
  
- Lancer le serveur local

- Créer votre dossier dans le dossier htdocs
![image](Images/image2.png)

- Copier/coller le contenu du dossier Wordpress dans le dossier que vous avez créé.
![image](Images/image3.png)

- Rendez-vous sur PHPMyAdmin pour créer une base de données
![image](Images/image4.png)

- Créer une base de donnée qui porte le nom de votre dossier
![image](Images/image5.png)

- vous pouvez quitter PHPMyAdmin
  
- Vous pouvez lancer votre premier site Wordpress en inscrivant l'url suivant :
    localhost/"nom du dossier" (ex: localhost/test)

- Compléter les champs suivant :  
        - Base de données : "nom de votre base de donnée"  
        - identifiant : c'est votre identifiant phpmyadmin  
        - mot de passe : mot de passe phpmyadmin  
        - Ne pas modifier les 2 derniers champs  
![image](Images/image6.png)

- Compléter les champs suivant :   
        - Titre du site : Choisissez un titre pour votre site (modifiable par la suite)  
        - Identifiant : Inscrivez ce que vous voulez (ex: Admin)  
        - Mot de passe : Choisissez un mot de passe très complexe (Si vous faites      juste un test, vous pouvez inscrire "admin")  
        - Si votre mot de passe est faible, cochez la case juste en dessous  
        - Inscrivez votre e-mail  
![image](Images/image7.png)

## Voilà, vous pouvez commencer à créer votre premier site WordPress !  


<h2>3. Réglages </h2>

<h3>:warning: Il est important d'enregistrer après chaque étapes</h3>

<h3>Général</h3>
<img src="https://user-images.githubusercontent.com/98603007/183042799-f246cabd-051d-47c9-8f80-05d3fdab8f2d.png">

On peut également modifier:
- La langue du site
- Le fuseaux horaire
- le format de l'heure et de la date

<h3>Lecture</h3>
<img src="https://user-images.githubusercontent.com/98603007/183045848-254254cc-ff52-4c03-bc48-0b3837161de6.png">
<img src="https://user-images.githubusercontent.com/98603007/183046667-ca96222b-f9f6-40c9-88ff-13a555e450ee.png">

<h3>Médias</h3>
<img src="https://user-images.githubusercontent.com/98603007/183047948-c59182be-c7bc-4ded-b740-a353835c6f3a.png">

<h3>Permaliens</h3>
<img src="https://user-images.githubusercontent.com/98603007/183050458-7b3f2ac3-9563-42ba-b37b-a1f930ced886.png">


# 4. Thème

- Pour avoir de chouette thème gratuit, il existe Envato Element.

![image](Images/envato_element.png)

- Vous pourrez dès lors avoir accès au thème gratuit ou par block gratuit.

![image](Images/ensemble_EvE.png)

- Vous pourrez choisir une catégorie spécifique ou faire une simple recherche.

![image](Images/categorie.png)

- Une fois votre thème choisis, il reste plus qu'a faire un "intall kit"

![image](Images/instal_kit.png)

- Vous pouvez cliqué sur "view kit"

![image](Images/view.png)

- Maintenant, vous aurez le choix entre plusieurs template en rapport avec le thème intaller. Vous pouvez évidemment regarder à quoi va ressembler le template avec de le choisir.

![image](Images/check_template.png)

# 5. Plugin

- Lorsque vous voulez faire un plugin, vous devez ouvrir dans votre éditeur de code (ex: VsCode), le dossier que vous avez crée dans "htdocs" ou "www".

![image](Images/wamp.png)

- Une fois dans ouvert dans votre éditeur, ouvrez ensuite le dossier que vous avez crée pour WordPress.

![image](Images/www_htdocs.png)

- Ensuite, vous allez dans wp-content, plugins puis vous créez un dossier qui contiendra votre plugin (ici c'est: "headerplugin").
- Vous ouvrez le dossier "headerplugin" et vous devez crée un fichier du même nom (attention de ne pas oublier le ".php").

![image](Images/makePlugin.png)

- Une fois ceci fait, vous devez nommé et définir certaine variables pour votre plugins ( voir ici: [Doc WordPress](https://developer.wordpress.org/plugins/plugin-basics/header-requirements/)).

![image](Images/init.png)

- Quand votre plugin est bien nommer/décris, il reste le code à faire et voici [un site](https://themeisle.com/blog/code-snippets-for-wordpress/) pour des petits tips utile. (dans l'exemple de cet exercice, j'ai pris le n°6)

![image](Images/exemple.png)

- Voilà, il ne reste plus qu'a activé votre plugin dans les extensions.

![image](Images/activation.png)
