# 0 - Mise en place

## 1.0. Pré-requis sur une machine locale en Ubuntu 14.04 LTS (64-bits):
### 1.0.1. Logiciels de virtualisation (:star:):

* Télécharger les logiciels suivants:
  - [Vagrant](https://releases.hashicorp.com/vagrant/1.9.1/vagrant_1.9.1_x86_64.deb)
  - [Virtual Box](http://download.virtualbox.org/virtualbox/5.1.14/virtualbox-5.1_5.1.14-112924~Ubuntu~trusty_amd64.deb)

* Les Installer:
  ```
  sudo dpkg -i <chemin>/virtualbox-5.1_5.1.*.deb
  sudo dpkg -i <chemin>/vagrant_1.9.1_x86_64.deb
  ```

### 1.0.2. Logiciels de dévelopement (:star:):

* Installer les packets suivants:
  ```
  sudo apt-get -y install git
  ```

* Télécharger l'IDE `Sublime Text 2`:
  - [Sublime Text 2](https://download.sublimetext.com/sublime-text_build-3126_amd64.deb)
  
* L'installer:
  ```
  sudo dpkg -i <chemin>/sublime-text_*_amd64.deb
  ```

### 1.0.3. Création d'un compte Github (:star::star::star:):

Aller sur [Github](https://github.com/) et créer un profil.

Ensuite dans cliquer sur mon compte (en haut à droite de la page) > Settings > SSH and GPG keys > [Suivre le tutoriel](https://help.github.com/articles/connecting-to-github-with-ssh/)


### 1.1. Initialisation du projet `Forum` (:star:):

* Créer un espace de travail et se rendre dedans:
  ```
  mkdir ~/workspace
  cd ~/workspace
  ```

* Cloner le projet:
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

