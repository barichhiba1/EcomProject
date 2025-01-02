
#  Projet ECOM Microservices

Ce projet implémente un système complet avec une architecture **microservices** et une interface utilisateur développée en **Angular** pour gérer 🧑‍💼 les clients, 🛍️ les produits, et 📦 les commandes.

---
## ⚙️ Partie Backend
### Fonctionnalités
1. **👤 Customer-Service** : Gestion complète des informations des clients (création, mise à jour, suppression).
2. **📦 Inventory-Service** : Gestion et suivi des stocks, mise à jour des produits disponibles.
3. **💳 Billing-Service** : Génération des factures, suivi des paiements et gestion des commandes.
4. **🌉 Gateway-Service** : Passerelle API utilisant Spring Cloud Gateway pour le routage et la sécurité.
5. **🔍 Eureka Discovery Service** : Service d'annuaire pour l'enregistrement et la découverte des microservices.
6. **🛠️ Configuration-Service** : Centralisation et gestion des configurations à partir d'un dépôt partagé.
   <img src="captures/fonct pro.png" width="500" height="auto">


### 📚 Technologies utilisées

- **🚀 Spring Boot** : Framework clé pour développer des microservices de manière rapide et structurée.
- **🗄️ Spring Data JPA** : Simplifie la gestion des bases de données relationnelles avec une interface intuitive.
- **🌐 Spring Data REST** : Automatise l'exposition des entités JPA sous forme d'API RESTful.
- **🛢️ H2 Database** : Base de données en mémoire, idéale pour les tests et le développement rapide.
- **🌩️ Spring Cloud** : Inclut des modules essentiels tels que Eureka (découverte de services), Gateway (passerelle API), et OpenFeign (communication entre services).
- **✍️ Lombok** : Élimine le code répétitif en générant automatiquement les getters, setters, etc.
- **📊 Spring Boot Actuator** : Fournit des outils pour le monitoring, les métriques, et la gestion des microservices.



### 🖼️ Démonstration Backend

Chaque microservice offre des fonctionnalités accessibles via des endpoints RESTful, permettant une interaction fluide et scalable entre les services.

<h3> ❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤ </h3>

<h1>Architecture du projet </h1>
<img src="captures/img_11.png">




<h1>-------------------------------------------------- </h1>

#### Customer-Service
- **API pour les clients** :
<img src="captures/img.png">

<img src="captures/img_1.png">

<img src="captures/img_2.png">
<img src="captures/img_3.png">
<img src="captures/img_9.png">

#### Inventory-Service
- **API pour les produits** :

<img src="captures/img_4.png">
<img src="captures/img_10.png">

#### Billing-Service
- **API pour les commandes** :  

<img src="captures/img_5.png">
<img src="captures/img_6.png">
<img src="captures/img_7.png">
<img src="captures/img_8.png">

<img src="captures/img_10.png">

#### config service  

<img src="captures/img_12.png">
<img src="captures/img_13.png">
<img src="captures/img_14.png">
<img src="captures/img_15.png">
<img src="captures/img_16.png">
<img src="captures/img_17.png">

## 💻 Partie Frontend

L'interface utilisateur est conçue avec **Angular**, garantissant une expérience utilisateur fluide, réactive et moderne. Ce choix permet de créer des applications dynamiques et performantes tout en facilitant la maintenance et l'évolutivité.
---

### Fonctionnalités
1. **Gestion des clients** : Affichage de la liste des clients.
2. **Gestion des produits** : Affichage de la liste des produits.
3. **Gestion des commandes** : Affichage des factures et des détails des commandes.
---

### 📚 Technologies utilisées
- **🅰️ Angular** : Framework pour le frontend.
- **📦 Bootstrap** : Design responsive et moderne.
---
### 🖼️ Démonstration Frontend

#### Products
<img src="captures/img_18.png">

#### Customers  
<img src="captures/img_19.png">

<img src="captures/img_20.png">

####  dropdown menu
<img src="captures/img_21.png">







<h3> ❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤ </h3>







