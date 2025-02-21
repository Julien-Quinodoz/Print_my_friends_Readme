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

Dans TON fichier `README.md`, insère la section suivante(## Derniers Followers GitHub) pour afficher dynamiquement les 10 derniers followers :

LE format et le nom doit être identique --->

                                                 ## Derniers Followers GitHub

### 6. Exécute manuellement le script via GitHub Actions

Si tu veux tester ou mettre à jour immédiatement la liste des 10 derniers followers, tu peux exécuter le script manuellement à partir de l'interface de GitHub Actions. Voici comment procéder :

1. **Accède à GitHub Actions** :
   Ouvre ton dépôt GitHub et va dans l'onglet **Actions** situé dans le menu en haut de ta page.

2. **Sélectionne le workflow** :
   Dans le panneau des workflows, tu verras une liste des workflows définis, y compris celui que tu as configuré pour mettre à jour les followers (`Update Followers List`).

3. **Exécute le workflow manuellement** :
   Clique sur le workflow **Update Followers List**. Tu devrais voir un bouton intitulé **Run workflow** sur la droite de la page. Clique dessus pour démarrer l'exécution du workflow manuellement.

4. **Vérifie l'exécution** :
   Une fois le workflow lancé, GitHub Actions commencera à exécuter les étapes définies dans le fichier YAML (y compris l'exécution du script Python). Tu peux suivre l'avancement et vérifier les logs en temps réel.

5. **Mise à jour immédiate** :
   Une fois l'exécution terminée, ton fichier `followers.yml` sera mis à jour avec les 10 derniers followers. Tu verras les modifications reflétées dans ton dépôt et dans ton `README.md` après un commit automatique.

Cela te permet de mettre à jour ta liste de followers immédiatement sans attendre l'exécution programmée du workflow.

## Points importants :

- **Maintien du format** : Assure-toi de garder le format de la section `## Derniers Followers GitHub` dans ton README. Cela permettra au script de fonctionner correctement.
- **Automatisation via GitHub Actions** : GitHub Actions s'occupera de l'exécution quotidienne, mais tu peux toujours lancer le script manuellement si besoin.
- **Utilisation du fichier `followers.yml`** : Ce fichier est généré et mis à jour à chaque exécution du script. Il contient la liste des 10 derniers followers, que tu peux utiliser pour personnaliser la présentation de tes followers dans ton `README.md`.

## Quelques astuces supplémentaires :

- **Mise à jour manuelle** : Si tu veux mettre à jour la liste des followers immédiatement, tu peux exécuter manuellement le workflow GitHub Action depuis l'interface GitHub (pas besoin d'attendre les 24 heures programmées).
- **Personnalisation** : N'hésite pas à personnaliser le script `update_followers.py` pour l'adapter à tes besoins spécifiques, par exemple pour filtrer certains types de followers ou pour modifier la façon dont ils sont affichés dans ton `README.md`.

---

### 🚀 Bonne chance avec ton projet ! Si ce dépôt t'a été utile, n'hésite pas à lui donner une étoile ⭐ pour encourager le développement futur et aider d'autres utilisateurs !

