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
  <tr><td><img src='https://github.com/SaperlipopetteMaSalopette.png' width='50' height='50'></td><td><strong>SaperlipopetteMaSalopette</strong></td><td><a href='https://github.com/SaperlipopetteMaSalopette'>Profil</a></td></tr>
<tr><td><img src='https://github.com/CODMAT23.png' width='50' height='50'></td><td><strong>CODMAT23</strong></td><td><a href='https://github.com/CODMAT23'>Profil</a></td></tr>
<tr><td><img src='https://github.com/Nesplee.png' width='50' height='50'></td><td><strong>Nesplee</strong></td><td><a href='https://github.com/Nesplee'>Profil</a></td></tr>
<tr><td><img src='https://github.com/Rodrigotari1.png' width='50' height='50'></td><td><strong>Rodrigotari1</strong></td><td><a href='https://github.com/Rodrigotari1'>Profil</a></td></tr>
<tr><td><img src='https://github.com/Cwilliam22.png' width='50' height='50'></td><td><strong>Cwilliam22</strong></td><td><a href='https://github.com/Cwilliam22'>Profil</a></td></tr>
<tr><td><img src='https://github.com/AwTaS.png' width='50' height='50'></td><td><strong>AwTaS</strong></td><td><a href='https://github.com/AwTaS'>Profil</a></td></tr>
<tr><td><img src='https://github.com/DIMFLIX-OFFICIAL.png' width='50' height='50'></td><td><strong>DIMFLIX-OFFICIAL</strong></td><td><a href='https://github.com/DIMFLIX-OFFICIAL'>Profil</a></td></tr>
<tr><td><img src='https://github.com/pasqualerossi.png' width='50' height='50'></td><td><strong>pasqualerossi</strong></td><td><a href='https://github.com/pasqualerossi'>Profil</a></td></tr>
<tr><td><img src='https://github.com/0yech.png' width='50' height='50'></td><td><strong>0yech</strong></td><td><a href='https://github.com/0yech'>Profil</a></td></tr>
<tr><td><img src='https://github.com/jelspace.png' width='50' height='50'></td><td><strong>jelspace</strong></td><td><a href='https://github.com/jelspace'>Profil</a></td></tr>
</table>
