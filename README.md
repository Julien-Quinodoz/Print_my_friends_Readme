<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com/?lines=Print+!+My+....+Friends!&center=true&size=25">
  </a>
</h1>
<div align="center">

---

# Créer un tableau des 10 derniers followers dans ton README !

Dans ce guide, tu apprendras à afficher automatiquement les 10 derniers followers de ton profil GitHub dans ton README à l’aide de GitHub Actions.

## Étapes à suivre :

### 1. Ajoute le script `update_followers.py`
Place ce script dans ton dépôt. Ce script récupère les informations des 10 derniers followers de ton profil GitHub via l'API GitHub. Si vous avez un problème avec "import requests" faite une recherche sur venv pyton.

### 2. Modifie le nom d'utilisateur dans le script
Ouvre `update_followers.py` et remplace `USERNAME` par ton propre nom d'utilisateur GitHub pour récupérer les bons followers.

### 3. Crée le dossier `.github/workflows`
N’oublie pas de créer ce dossier à la racine de ton dépôt. Le point (`.`) au début du nom du dossier est essentiel.

### 4. Ajoute le fichier `update-followers.yml` dans `.github/workflows`
Ce fichier YAML va contenir la configuration de GitHub Actions, qui exécutera ton script une fois par jour. Utilise le cron pour automatiser l'exécution.

### 5. Ajoute un bloc "Derniers Followers GitHub" dans ton README

Dans TON fichier `README.md`, insère la section suivante(

## Derniers Followers GitHub

<table>
  <tr><th>Avatar</th><th>Nom d'utilisateur</th><th>Profil</th></tr>
  <tr><td><img src='https://github.com/K1rsN7.png' width='50' height='50'></td><td><strong>K1rsN7</strong></td><td><a href='https://github.com/K1rsN7'>Profil</a></td></tr>
<tr><td><img src='https://github.com/DIMFLIX.png' width='50' height='50'></td><td><strong>DIMFLIX</strong></td><td><a href='https://github.com/DIMFLIX'>Profil</a></td></tr>
<tr><td><img src='https://github.com/cloutswagsauce.png' width='50' height='50'></td><td><strong>cloutswagsauce</strong></td><td><a href='https://github.com/cloutswagsauce'>Profil</a></td></tr>
<tr><td><img src='https://github.com/Maka-77x.png' width='50' height='50'></td><td><strong>Maka-77x</strong></td><td><a href='https://github.com/Maka-77x'>Profil</a></td></tr>
<tr><td><img src='https://github.com/seckinyasar.png' width='50' height='50'></td><td><strong>seckinyasar</strong></td><td><a href='https://github.com/seckinyasar'>Profil</a></td></tr>
<tr><td><img src='https://github.com/helallao.png' width='50' height='50'></td><td><strong>helallao</strong></td><td><a href='https://github.com/helallao'>Profil</a></td></tr>
<tr><td><img src='https://github.com/pasqualerossi.png' width='50' height='50'></td><td><strong>pasqualerossi</strong></td><td><a href='https://github.com/pasqualerossi'>Profil</a></td></tr>
<tr><td><img src='https://github.com/0yech.png' width='50' height='50'></td><td><strong>0yech</strong></td><td><a href='https://github.com/0yech'>Profil</a></td></tr>
<tr><td><img src='https://github.com/jelspace.png' width='50' height='50'></td><td><strong>jelspace</strong></td><td><a href='https://github.com/jelspace'>Profil</a></td></tr>
<tr><td><img src='https://github.com/schalkventer.png' width='50' height='50'></td><td><strong>schalkventer</strong></td><td><a href='https://github.com/schalkventer'>Profil</a></td></tr>
</table>
