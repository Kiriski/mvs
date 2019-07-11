
# Vagrant documentation

## concepts

object une machine virtuelle 

-> besoin os donc lequel ? unbuntu

-> ou on va la lancer ? VirtualBox

-> un logiciel intermediare qui va faire la conf pour nous ? vagrant


1. télécharger l'os "unbuntu"

2. configurer un machine virtuelle -> avec des ressources et oS

3. la configuration elle est sauvegardé dans un fichier

## procedure réelle avec commandes

1ère étape  : configuration de la mv

vagrant init ubuntu/trusty64
(tag de l'os pour initialiser la machine virtuelle)
Cette commande crée un fichier Vagrantfile qui comporte les détails de la configuration.


2ème étape  : démarrage de la mv (installation, si jamais installée)

vagrant up

3ème étape  : de connecter à la machine à partir du terminal (prendre le controle à distance de la mv)

vagrant ssh

