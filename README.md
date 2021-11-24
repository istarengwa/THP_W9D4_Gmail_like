# Projets : Gmail-like en AJAX
  
# 1. Introduction

Pour ce projet, nous allons te demander de faire un Email Viewer qui n'est ni plus ni moins qu'une version ultra basique de Gmail. Globalement l'appli affichera une seule et unique page avec 2 colonnes :

* Une colonne contenant la liste des emails en base ;
* Une colonne affichant le contenu de l'email sur lequel l'utilisateur vient de cliquer.

# 2. Le projet

2.1. Une appli Rails

Pour te simplifier la vie, tu vas continuer sur l'application Rails d'hier (la to do list) : cela t'évitera de refaire les manipulations et branchements habituels (que tu connais à présent par coeur).
Crées un model email ayant des attributs object (string), et body (text). On ira pas tellement plus loin pour le back, après tout on bosse sur AJAX là ! Fais-toi un petit seed pour mettre en base quelques emails.

Maintenant root ton projet sur email#index, et génère le controller et la view qui correspondent. On va pouvoir bosser !

* Rails version 5.2.6
* Ruby version 2.7.4

# Installation

* bundle install
* rails db:create db:migrate db:seed
* rails server

# Information

* Création de mail par bouton
* Suppression de mail par bouton
* Le tout en affichage AJAX
