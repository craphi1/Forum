# 0 - Mise en place

## 1.0. Pré-requis sur la machine locale:
### 1.0.1. Logiciels de virtualisation (:star:):
#### Linux (Ubuntu 14.04):
* Télécharger les logiciels suivants:
  - [Virtual Box](http://download.virtualbox.org/virtualbox/5.1.14/virtualbox-5.1_5.1.14-112924~Ubuntu~trusty_amd64.deb)
  - [Vagrant](https://releases.hashicorp.com/vagrant/1.9.1/vagrant_1.9.1_x86_64.deb)

* Les Installer:
  ```
  sudo dpkg -i <chemin>/virtualbox-5.1_5.1.*.deb
  sudo dpkg -i <chemin>/vagrant_1.9.1_x86_64.deb
  ```

#### Windows:

* Télécharger et installer les logiciels suivants:
  - [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
  - [Vagrant](https://www.vagrantup.com/downloads.html)

### 1.0.2. Logiciels de développement (:star:):

#### Linux (Ubuntu 14.04):

* Installer les packets suivants:
  ```
  sudo apt-get -y install git
  ```

* Télécharger l'IDE `Sublime Text 2` (Interface de développement):
  - [Sublime Text 2](https://download.sublimetext.com/sublime-text_build-3126_amd64.deb)
  
* L'installer:
  ```
  sudo dpkg -i <chemin>/sublime-text_*_amd64.deb
  ```

#### Windows:

* Télécharger et installer les logiciels suivants:
  - [Git](https://git-scm.com/download)
  - [Sublime Text 2](http://www.sublimetext.com/2)

### 1.0.3. Création d'un compte Github (:star:):

Aller sur [Github](https://github.com/) et créer un compte.

> Optionnel: Cliquer sur mon compte (en haut à droite de la page) > Settings > SSH and GPG keys > [Suivre le tutoriel](https://help.github.com/articles/connecting-to-github-with-ssh/)

## 1.1. Initialisation du projet `Forum` (:star:):

* Créer un espace de travail (nouveau dossier) et se rendre dedans:
  ```
  mkdir ~/workspace
  cd ~/workspace
  ```

* Cloner le projet en utilisant l'invite de commande:
  ```
  git clone git@github.com:<Utilisateur>/Forum.git
  ```
 
* Aller dans `<forum>/0_setup`:
  ```
  cd <forum>/0_setup
  ```

* Lancer la commande vagrant:
  ```
  vagrant up
  ```

