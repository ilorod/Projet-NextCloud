# Explication du Projet - TP Docker Nextcloud

## 👤 Nom : Ilona Rodriguès  
## 💼 Sujet : Déploiement d'une solution Nextcloud avec Docker et Docker Compose

---

## 🔧 Objectif du TP

Mettre en place un service cloud personnel (Nextcloud) en utilisant des conteneurs Docker. Le projet vise à apprendre à :
- Créer des conteneurs manuellement avec `docker run`
- Gérer la persistance des données via des volumes Docker
- Structurer une architecture multi-conteneurs avec `docker-compose.yml`
- Ajouter des outils de supervision/administration (Adminer, Portainer)

---

## ⚙️ Ce que j'ai fait

### ✅ Étape 1 - Déploiement simple
- Lancement de deux conteneurs : **Nextcloud** et **MariaDB**
- Utilisation de la commande `docker run`
- Vérification de l’interface via le port `8082`

### ✅ Étape 2 - Volumes
- Ajout de volumes Docker pour conserver les données
- Test : j’ai supprimé et relancé les conteneurs → les données ont été conservées ✅

### ✅ Étape 3 - Docker Compose
- Création d’un fichier `docker-compose.yml`
- Tout est lancé automatiquement avec une seule commande : `docker compose up -d`

### ✅ Étape 4 - Outils supplémentaires
- Ajout de **Adminer** : interface web pour accéder à la base de données
- Ajout de **Portainer** : tableau de bord pour voir et gérer mes conteneurs Docker

---

## 📁 Contenu du dépôt GitHub

Le dépôt contient :
- Le fichier `docker-compose.yml`
- Un fichier `ilona-rodrigues.md` expliquant toutes les étapes
- Un dossier word envoyer par e-mail avec les captures d’écran demandées

Lien du dépôt GitHub : [https://github.com/ilorod/Projet-NextCloud](https://github.com/ilorod/Projet-NextCloud)

---

## 📌 Résultat

Le service Nextcloud est :
- Fonctionnel
- Persitant
- Facilement redéployable
- Supervisé avec des outils externes

Ce projet m’a permis de bien comprendre le fonctionnement de Docker, des volumes, de la base de données, et l’intérêt de `docker-compose`.

---

