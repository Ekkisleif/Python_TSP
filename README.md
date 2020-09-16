# Python TSP
  
## Prise en main de Ubuntu
Une commande essentielle dans ubuntu est **CTRL + ALT + T** qui permet d'ouvrir le terminal.  
Il ne faut bien entendu pas avoir peur à utiliser des lignes de commandes pour faire certaines actions dans un environnement Linux.  
  
### Utilisation de APT
Le gestionnaire de *packages* **apt** permet la mise à jour des Packages d'Ubuntu mais aussi permet d'installer de nombreuses applications (comme vlc,..) qui sont déjà dans les librairies de Ubuntu. Le fonctionnement des packages d'Ubuntu est très proche de celui des application du Google Play Store et de l'Apple Store.
  
On va donc commencer par la mise à jour de Ubuntu avec 2 commandes (à exécuter dans le terminal de Ubuntu et l'une après l'autre):
``` sh
sudo apt update
sudo apt upgrade
```

**sudo** : permet de se mettre en mode *root* c'est à dire qu'il vous autorise à modifier votre système. (sudo signifie "super-user do", soit "faire en tant que super-utilisateur")  
**update** : permet de lire les différentes "*librairies*" citées précédemment afin de voir si des *Packages* doivent être mis à jour.  
**upgrade** : permet de mettre à jour les packages susnommés.  
#### ATTENTION, l'arrêt de la commande *sudo apt upgrade* à cause d'un problème de connexion ou autre peut entrainer des problèmes dans Ubuntu (c'est aussi le cas si vous arrêtez la mise à jour Windows au milieu)  
#### ATTENTION², bien penser que seul la commande *sudo apt upgrade* installe les mises à jour, *sudo apt update* ne fait que regarder s'il en existe.

### Vérification de Python
Pour vérifier que python est bien installé, il suffit d'exécuter la commande :
``` sh
python3 --version
```
Il est aussi intéressant d'installer pip qui est un gestionnaire de librairies très utile à Python.
``` sh
sudo apt install python3-pip
```
Pour ensuite installer une librairie, il suffit de faire une petite commande.
``` sh
pip3 install <la_librairie_a_installer>
```  
Il faut remplacer **<la_librairie_a_installer>** par le nom de la librairy à installer
#### Note: Il est possible que ce soit la commande pip au lieu de pip3 (ce qui est peu probable car vous devriez avoir tout python3)
### Installation des librairies utiles pour les cours (rajouts éventuels au cour de l'année)
``` sh
pip3 install numpy
pip3 install matplotlib
pip3 install scipy
```
## Pour ceux qui souaitent utiliser Notebook Jupiter
installer la librairy à Python3
``` sh
pip3 install jupyter
```
installer le logiciel sur Linux
``` sh
sudo apt install jupyter
```
Il suffira ensuite de taper dans le terminale : **jupyter notebook**

