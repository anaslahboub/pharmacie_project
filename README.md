# pharmacie_project
# Cahier des Charges - Système de Pharmacie en Ligne

## Introduction
Le présent cahier des charges détaille les spécifications fonctionnelles et techniques pour le développement d’un système de pharmacie en ligne, permettant aux patients d’envoyer leurs ordonnances et de récupérer les traitements prescrits dans une pharmacie partenaire.

## A. Objectifs du Système
Le système doit permettre :
- Aux patients de soumettre leurs ordonnances via une application mobile ou une interface web.
- Aux pharmaciens de recevoir et traiter les ordonnances, notifier les patients du statut de la commande et du montant total.
- À un administrateur de gérer les utilisateurs, les pharmacies, et de changer le statut d’une pharmacie.

## B. Description des Acteurs
- **Administrateur** : Gère les informations et le statut des utilisateurs et pharmacies via une interface web.
- **Patient** : Utilise l’application mobile ou une interface web pour soumettre une ordonnance, suivre sa commande, et consulter l’historique de ses commandes.
- **Pharmacien** : Utilise une application mobile ou une interface web pour consulter les ordonnances reçues, préparer les traitements et notifier le patient.

## C. Fonctionnalités Détailées

### 1. Fonctionnalités de l’Administrateur
- Consulter les informations des utilisateurs
- Visualiser la liste des utilisateurs et leurs informations personnelles
- Consulter la liste des pharmacies
- Consulter les informations d’une pharmacie
- Changer le statut d’une pharmacie (active ou non active)

### 2. Fonctionnalités du Patient
- S’enregistrer et gérer son compte
- Consulter la carte des pharmacies partenaires
- Prendre une photo de l’ordonnance (application mobile)
- Envoyer l’ordonnance en format image
- Afficher la localisation des pharmacies avec filtres (nom, statut, distance, zone…)
- Suivre l’état de sa commande
- Consulter l’historique de ses commandes
- Recevoir des notifications par email ou SMS

### 3. Fonctionnalités du Pharmacien
- Consulter les ordonnances reçues
- Préparer le traitement prescrit
- Notifier le patient de l’état de la commande (en préparation, prête à récupérer, etc.)
- Indiquer le montant total de la commande

## D. Notifications et Communication
- Notifications pour la pharmacie : réception d’ordonnance
- Mises à jour du statut de la commande envoyées au patient

## E. Spécifications Techniques

### 1. Interfaces
- **Application mobile** : Android & iOS
- **Interface web** : pour patients et pharmaciens

## F. Sécurité et Confidentialité
- Authentification et autorisation
- Chiffrement des données personnelles et des images
- Conformité aux réglementations locales sur les données de santé

## G. Infrastructure de Notification
- Service de notifications email et SMS via services tiers

## H. Architecture Technologique
- **Backend** : Java, EJB, MySQL, Servlets, JSP
- **Frontend Web** : React.js, JSP, MVC
- **Application Mobile** : Flutter, SQLite
- **Notifications** : Email, SMS
- **Serveur d’Application** : Tomcat ou WildFly

## Conclusion
Ce cahier des charges définit les grandes lignes et exigences de développement du système de pharmacie en ligne. Les fonctionnalités décrites sont destinées à offrir une expérience utilisateur fluide pour les patients, pharmaciens et l’administrateur, tout en assurant la sécurité et la confidentialité des données de santé.
