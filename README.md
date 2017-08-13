# Bot 18-25 PHP

## Fonctionnalités
* Envois un message en fonction du nombre de réponses
* Bypass le script anti-bot.

## Extensions PHP nécessaires :
* PHP
* PHP-CURL

## Installation
Pour utiliser ce script PHP, il vous faudra un serveur web. Le script peut être utilisé depuis un client web, mais il est recommandé de l'utiliser en version CLI.

### Linux (Serveur web local)
Installer un serveur web à l'aide de Apache2/Nginx.
Installer ensuite les extensions ci-dessus.
Passer ensuite à la configuration.

### Windows (Serveur web local)
1. Première solution : installer un serveur comme http://www.wampserver.com/.
1. Deuxième solution (Windows 10 uniquemment) : Utiliser le shell bash Ubuntu disponible sous windows 10 https://korben.info/installer-shell-bash-linux-windows-10.html.

Passer ensuite à la configuration.

## Configuration
1. Téléchargez le script PHP et placez-le dans un dossier
1. Editez le script `bot.php` et placez les identifiants de votre COMPTE BOT comme ci-dessous :
    ```
   $username = "PSEUDO";
   $userpassword = "MOT DE PASSE";
    ``` 
1. OPTIONNEL : Editez le `$MAX_RESPONSES = 1;`, cela correspond au nombre maximum de réponses sur le topic où le bot poste. 0 = Message first uniquement. 1 = Message first & second uniquement. 20 = Première page uniquement etc..
4. Créez un fichier `message.txt`
4. Editez ensuite le fichier `message.txt` et placez y votre message :
    ```
    EXEMPLE DE MESSAGE
    :rire:
    ```
6. Vous pouvez ensuite lancer le script PHP.

**Astuce : Vous pouvez lancer plusieurs bot en créant un autre dossier et en répétant la manipulation.**

**Astuce 2: La connexion au compte sur le navigateur n'est pas nécessaire, le bot s'y connecte automatiquement.**

## Note : Ne mettez pas plus de 8 images dans le message à poster où le script anti-bot vous considérera comme tel.
## Note 2 : Si vous utilisez le bot depuis le naviguateur, il se peut que le script affiche "Identifiants incorrects" ou n'affiche rien mais fonctionne correctement, ne rechargez pas la page, et vérifiez si le bot fonctionne.

