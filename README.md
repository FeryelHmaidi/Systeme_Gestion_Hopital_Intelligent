# Système de Gestion d'un Hôpital Intelligent

Projet réalisé dans le cadre du cours d'Ingénierie des Bases de Données (MI2)
à la Faculté des Sciences Mathématiques, Physiques et Naturelles de Tunis.

# Contexte

Ce projet modélise le fonctionnement interne d'un hôpital : 
de l'admission d'un patient jusqu'à sa prescription médicale, 
en passant par la gestion des médecins et des services.

# Base de données

Les tables principales :
- Service, Patient, Medecin
- Hospitalisation, RendezVous
- Prescription, Ligne_Prescription, Medicament

# Ce que j'ai implémenté

- Curseurs avec FOR UPDATE et WHERE CURRENT OF
- Triggers sur les opérations critiques
- Package PKG_HOPITAL regroupant les procédures et fonctions
- Gestion des exceptions Oracle
- Jeu de tests complet

# Fichiers

- `1000-complet (2).sql` — création des tables, package, triggers et procédures
- `100-test.sql` — insertion des données et tests complets

# Comment exécuter

1. Se connecter à Oracle avec les droits suffisants
2. Lancer `1000-complet (3).sql` pour créer les tables et le package
3. Lancer `100-test.sql` pour insérer les données et tester

# Environnement

- Oracle Database
- VS Code avec Oracle Developer Tools

[LinkedIn](https://linkedin.com/in/feryel-hmaidi-25b298330)
