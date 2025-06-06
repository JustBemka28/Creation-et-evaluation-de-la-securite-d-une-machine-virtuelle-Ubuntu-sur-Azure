# 🔐 Création et évaluation de la sécurité d'une machine virtuelle Ubuntu sur Azure

Projet réalisé dans le cadre du cours **CYB1123 – Sécurité de l’infonuagique et des services Web** à l’Université du Québec en Outaouais.

## 🎯 Objectif

Ce projet vise à documenter toutes les étapes de la création et de l’analyse de sécurité d'une VM Ubuntu 24.04 nommée `Ubuntu-Pro-24.04` hébergée sur **Microsoft Azure**, avec des réflexions sur les risques, les bonnes pratiques, et les mesures de sécurité à mettre en place.

## 🛡️ Technologies utilisées

- Microsoft Azure (VM, App Services, Network Security Groups)
- Ubuntu 24.04 LTS
- SSH (clé publique/privée)
- Principes de base de la sécurité infonuagique

## 🧩 Contenu du rapport

### Partie 1 – Informations à demander au client pour l’évaluation de sécurité
- Politique de sécurité appliquée (ex : CIS, ISO 27001)
- Authentification utilisée (MFA, SSH key, etc.)
- Outils de scans externes (en plus d’Azure Security Center)
- Contraintes réglementaires

### Partie 2 – Évaluation de la sécurité de la VM
- Utilisation de clés SSH ✅
- Port SSH uniquement ouvert ✅
- Absence de gestion active des vulnérabilités ❌
- Recommandations : activer des pare-feux, surveillance, journalisation

### Partie 3 – Étapes de création avec captures
- 🎓 Connexion avec compte étudiant
- ⚙️ Configuration de l’abonnement Azure
- 🖥️ Création et propriétés de la VM
- 🌐 Connexion SSH via IP publique : `20.151.79.48`
- 📋 Liste des ressources dans Azure






