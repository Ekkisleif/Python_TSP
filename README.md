# Python TSP
  
## Prise en main de Ubuntu
Une commande essentielle dans ubuntu est **CTRL + ALT + T** qui permet d'ouvrir le terminal.  
Il ne faut bien entendu pas avoir peur à utiliser des lignes de commandes pour faire certaines actions dans un environnement Linux.  
  
### Utilisation de APT
Le gestionnaire de *packages* **apt** permet la mise à jour des applications de Ubuntu mais aussi permet d'installer de nombreuses applications (comme vlc,..) qui sont déjà dans les librairies de Ubuntu. Le fonctionnement des packages d'Ubuntu est très proche de celui des application du Google Play Store et de l'Apple Store.
  
On va donc commencer par la mise à jour de Ubuntu avec 2 commandes (à exécuter dans le terminal de Ubuntu et l'une après l'autre):
``` sh
sudo apt update
sudo apt upgrade
```

**sudo** : permet de se mettre en mode *root* c'est à dire qu'il vous autorise à modifier votre système.  
**update** : permet de lire les différentes "*librairies*" citées précédemment afin de voir si des *Packages* doivent être mis à jour.  
**upgrade** : permet de mettre à jour les packages susnommés.  
#### ATENTION, l'arrêt de la commande *sudo apt upgrade* à cause d'un problème de connexion ou autre peut entrainer des problèmes dans Ubuntu (c'est aussi le cas si vous arrêtez la mise à jour Windows au milieu)

### Vérification de Python
Pour vérifier que python est bien installé, il suffit d'exécuter la commande :
``` sh
python3 --version
```
Il est aussi intéressant d'installer pip qui est un gestionnaire de librairies très utile à Python.
``` sh
sudo apt install python3-pip
```
