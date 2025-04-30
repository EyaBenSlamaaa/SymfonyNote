# 📝 Compte Rendu - Projet Symfony Notes

## 📌 Objectif
    Créer une application web simple permettant à un utilisateur :
        - d’ajouter, modifier et supprimer des notes,
        - de gérer l’authentification (connexion / inscription / déconnexion),
        - de visualiser toutes ses notes dans une interface responsive et esthétique.

---

## 🧱 Technologies utilisées
    - **Symfony 6+**
    - **Twig** pour le templating
    - **Bootstrap 5.3.3** pour le design responsive
    - **Bootstrap Icons** pour les icônes (edit, delete, etc.)
    - **CSS personnalisé** pour une meilleure présentation

---

## ⚙️ Fonctionnalités réalisées

### 🔐 Authentification
    - ✅ Page de connexion avec vérification de l'identifiant
    - ✅ Page d'inscription avec enregistrement sécurisé
    - ✅ Déconnexion avec suppression de session

### 🗂️ Gestion des notes
    - ✅ Création d'une note (formulaire sécurisé avec `textarea`)
    - ✅ Liste des notes sous forme de grille (`grid layout`)
    - ✅ Modification d'une note avec préremplissage
    - ✅ Suppression avec confirmation JavaScript

### 🎨 Interface utilisateur
     - ✅ Arrière-plan illustré (`bg.svg`) avec style propre
     - ✅ Utilisation d’icônes Bootstrap : `bi-pencil-square`, `bi-trash`, `bi-clipboard2-plus`
     - ✅ Comportement responsive sur mobiles
     - ✅ Boutons stylisés (edit, delete, login, logout)

---

## 📂 Organisation du code

     - `base.html.twig` : layout principal (header, navbar, footer, CSS/JS)
     - `home.html.twig` : page d'accueil avec affichage des notes
     - `notes_new.html.twig` : formulaire pour ajouter une note
     - `notes_edit.html.twig` : formulaire pour modifier une note
     - `style.css` : personnalisation des composants Bootstrap

---

## ✅ Améliorations futures
    - 🔒 Hashage de mot de passe (si non implémenté)
    - 🔍 Ajout d'une barre de recherche pour filtrer les notes
    - 🧹 Implémentation du soft delete (archivage au lieu de suppression)
    - 🗃️ Tri et pagination des notes

---

## 👤 Réalisé par
    Eya ben slama

