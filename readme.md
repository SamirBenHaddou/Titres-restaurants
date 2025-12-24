# Master RH - Plateforme de Gestion des Ressources Humaines

## Présentation du Projet

### 🎯 Objectif de la Plateforme

**Master RH** est une solution web complète dédiée à la gestion des ressources humaines. Cette plateforme unifie la gestion des notes de frais professionnels, des tickets restaurant et du recrutement de collaborateurs dans une interface moderne et intuitive. L'application vise à simplifier et digitaliser les processus RH courants pour les entreprises de toutes tailles.

---

## 💻 Technologies Utilisées

### **Frontend**

- **HTML5** - Structure sémantique des pages web
- **CSS3** - Design moderne avec animations et effects visuels avancés
- **JavaScript (Vanilla)** - Logique client et interactions dynamiques
- **Responsive Design** - Adaptabilité sur tous types d'appareils

### **Stockage des Données**

- **LocalStorage** - Sauvegarde automatique côté client
- **JSON** - Format d'import/export des données
- **Système de fichiers** - Export PDF et sauvegarde

### **Bibliothèques et Outils**

- **CSS Grid & Flexbox** - Mise en page moderne et flexible
- **Calculs automatiques** - Algorithmes de calcul fiscal intégrés
- **API Navigateur** - Gestion des fichiers et impressions

---

## ⚡ Modules Principaux

### **1. 📝 Gestionnaire de Notes de Frais**

#### Fonctionnalités Clés :

- **Calcul automatique des frais kilométriques** selon le barème fiscal 2025
- **Gestion multi-types de frais** : transport, repas, hébergement, formation, etc.
- **Configuration véhicule** avec calcul dynamique selon la puissance fiscale
- **Saisie intuitive** avec validation en temps réel
- **Export PDF professionnel** avec signatures et récapitulatifs

#### Caractéristiques Techniques :

- Barème fiscal intégré avec 3 tranches de calcul
- Interface de saisie adaptative selon le type de frais
- Validation automatique des montants
- Totaux calculés en temps réel
- Format d'export standardisé

### **2. 🍽️ Gestionnaire de Tickets Restaurant**

#### Fonctionnalités Avancées :

- **Calcul automatique des jours ouvrés** avec prise en compte des jours fériés français
- **Gestion multi-salariés** avec suivi individuel
- **Périodes personnalisables** : trimestrielles, semestrielles, annuelles
- **Saisie rapide mensuelle** via modal dédié
- **Tableaux de bord** avec statistiques temps réel

#### Algorithmes Intégrés :

- Calcul des jours fériés français (fixes et mobiles)
- Algorithme de Butcher pour le calcul de Pâques
- Gestion des périodes chevauchant deux années
- Calcul automatique des droits et soldes

### **3. 👥 Module de Recrutement** _(En développement)_

#### Fonctionnalités Prévues :

- **Gestion des candidatures** avec suivi du processus
- **Base de données candidats** avec filtres avancés
- **Planification d'entretiens** avec notifications
- **Évaluation standardisée** avec grilles de critères
- **Reporting** et statistiques de recrutement

---

## 🏗️ Architecture Technique

### **Structure Modulaire**

```
master-rh/
├── modules/
│   ├── frais/
│   │   ├── index.html (Gestionnaire de frais)
│   │   └── styles.css
│   ├── tickets-restaurant/
│   │   ├── index.html (Gestionnaire tickets)
│   │   └── styles.css
│   └── recrutement/ (À développer)
├── assets/
│   ├── css/common.css
│   └── js/utils.js
└── README.md
```

### **Fonctionnalités Techniques Transversales**

- **Sauvegarde automatique** dans le navigateur
- **Import/Export JSON** pour transfert de données
- **Responsive design** adaptatif
- **Calculs temps réel** sans rechargement
- **Interface utilisateur moderne** avec micro-animations

---

## 🎨 Points Forts Techniques

### **Expérience Utilisateur**

- **Interface moderne** avec gradients et effets visuels
- **Feedback temps réel** sur toutes les actions
- **Navigation intuitive** avec raccourcis clavier
- **Design adaptatif** pour mobile, tablette et desktop

### **Fonctionnalités Avancées**

- **Calculs fiscaux automatisés** conformes à la législation 2025
- **Gestion des jours fériés** avec algorithmes complexes
- **Export PDF** avec mise en forme professionnelle
- **Système de raccourcis** pour saisie rapide

### **Robustesse et Fiabilité**

- **Validation des données** en temps réel
- **Gestion d'erreurs** complète
- **Sauvegarde redondante** (locale + export)
- **Code modulaire** et maintenable

---

## 📊 Tableaux de Bord et Reporting

### **Notes de Frais**

- **Récapitulatif dynamique** par type de frais
- **Totaux automatiques** avec répartition kilométrique/autres
- **Statistiques** : nombre de lignes, kilomètres parcourus
- **Export formaté** avec validation hiérarchique

### **Tickets Restaurant**

- **Vue consolidée multi-salariés**
- **Calculs de soldes** positifs/négatifs
- **Périodes flexibles** avec raccourcis (T1, T2, S1, S2)
- **Totaux généraux** en temps réel

---

## 🚀 Cas d'Usage Métier

### **Pour les Services RH**

- Centralisation de la gestion administrative
- Automatisation des calculs réglementaires
- Traçabilité complète des opérations
- Reporting instantané pour la direction

### **Pour les Salariés**

- Saisie simplifiée des frais professionnels
- Suivi transparent des tickets restaurant
- Interface self-service intuitive
- Export personnel des documents

### **Pour la Comptabilité**

- Données structurées et validées
- Calculs conformes aux barèmes fiscaux
- Export direct vers systèmes comptables
- Audit trail complet

---

## 🔧 Configuration et Personnalisation

### **Paramètres Configurables**

- **Barèmes fiscaux** : mise à jour annuelle automatique
- **Jours fériés** : adaptation selon localisation
- **Types de frais** : personnalisation selon entreprise
- **Niveaux d'approbation** : workflow modulable

### **Options d'Integration**

- **Export multi-formats** : PDF, JSON, CSV
- **Import de données** existantes
- **Synchronisation** avec systèmes tiers
- **API** pour intégrations futures

---

## 💡 Roadmap et Évolutions

### **Phase 2 - Court Terme**

- **Module Recrutement** complet
- **Notifications automatiques**
- **Workflow d'approbation** multi-niveaux
- **Thèmes personnalisables**

### **Phase 3 - Moyen Terme**

- **Application mobile** responsive
- **Intégration SIRH** existants
- **Analytics avancés** et KPI
- **Multi-entreprises** avec isolation des données

### **Phase 4 - Long Terme**

- **Intelligence artificielle** pour optimisation
- **Blockchain** pour traçabilité
- **API publique** pour développeurs
- **Marketplace** de modules additionnels

---

## 🏆 Avantages Concurrentiels

### **Avantages de l'Architecture BDD**

- **Persistance sécurisée** : données protégées côté serveur
- **Multi-utilisateurs** : gestion des droits et accès simultanés
- **Sauvegarde centralisée** : pas de perte de données locale
- **Synchronisation temps réel** entre utilisateurs
- **Sécurité renforcée** : authentification et chiffrement
- **Scalabilité** : support de volumes importants
- **Audit complet** : traçabilité de toutes les opérations

### **Facilité d'Usage**

- **Interface intuitive** sans formation nécessaire
- **Raccourcis intelligents** pour utilisateurs avancés
- **Multi-device** avec synchronisation
- **Support multilingue** (prévu)

### **Conformité Réglementaire**

- **Barèmes fiscaux** toujours à jour
- **Calculs certifiés** conformes URSSAF
- **Audit trail** complet
- **RGPD ready** avec données locales

---

## 📈 Métriques et Performance

### **Objectifs de Performance**

- Temps de chargement < 2 secondes
- Calculs temps réel < 100ms
- Export PDF < 5 secondes
- Interface responsive à 100%

### **Indicateurs de Succès**

- Réduction de 80% du temps de saisie
- Élimination des erreurs de calcul
- Satisfaction utilisateur > 95%
- Adoption enterprise en 30 jours

---

**Master RH** représente l'évolution naturelle de la gestion RH vers une solution digitale, moderne et centrée sur l'expérience utilisateur, tout en maintenant la rigueur et la conformité exigées par le domaine des ressources humaines.
