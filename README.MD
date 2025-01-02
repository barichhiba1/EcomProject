
<h3> ❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤ </h3>
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Architecture Backend</title>
</head>
<body>
    <h1>Architecture Backend</h1>
    <p>L'architecture de l'application backend est composée des services suivants :</p>

    <ul>
        <li>
            <h2>1.1. customer-service</h2>
            <p>
                Le service <strong>customer-service</strong> gère toutes les opérations liées aux clients. 
                Il permet de créer, lire, mettre à jour et supprimer les informations des clients. 
                Ce service expose des endpoints RESTful pour permettre aux autres services d’interagir avec les données des clients.
            </p>
        </li>
        <li>
            <h2>1.2. inventory-service</h2>
            <p>
                Le service <strong>inventory-service</strong> est responsable de la gestion de l’inventaire des produits. 
                Il suit les quantités de stock disponibles, met à jour les informations sur les produits, 
                et traite les demandes des utilisateurs concernant les articles en stock.
            </p>
        </li>
        <li>
            <h2>1.3. gateway-service</h2>
            <p>
                Le service <strong>gateway-service</strong> agit comme un point d’entrée pour toutes les demandes externes. 
                Il fonctionne comme une API Gateway qui redirige les requêtes HTTP vers les services internes appropriés, 
                tout en offrant des fonctionnalités comme la gestion des autorisations, des rôles, et le routage des requêtes.
            </p>
        </li>
        <li>
            <h2>1.4. discovery-service</h2>
            <p>
                Le service <strong>discovery-service</strong>, basé sur Eureka, est une solution de découverte de services. 
                Il permet à chaque microservice de s’enregistrer automatiquement dans un registre de services, 
                facilitant ainsi la communication entre services sans dépendre d’URLs codées en dur.
            </p>
        </li>
        <li>
            <h2>1.5. billing-service</h2>
            <p>
                Le service <strong>billing-service</strong> gère les factures des clients. 
                Il permet de générer des factures en fonction des achats et de suivre les paiements associés. 
                Ce service expose des endpoints pour récupérer les factures et traiter les paiements.
            </p>
        </li>
        <li>
            <h2>1.6. config-service</h2>
            <p>
                Le service <strong>config-service</strong> centralise et gère la configuration de tous les microservices. 
                Les paramètres de configuration sont stockés dans un dépôt Git ou un autre système de gestion, 
                et distribués dynamiquement aux services lors de leur démarrage.
            </p>
        </li>
    </ul>
</body>
</html>


<img src="captures/img_11.png">

<h1>------------------------------------------ </h1>
<img src="captures/img.png">

<img src="captures/img_1.png">

<img src="captures/img_2.png">


<img src="captures/img_3.png">
<img src="captures/img_4.png">
<img src="captures/img_5.png">
<img src="captures/img_6.png">
<img src="captures/img_7.png">
<img src="captures/img_8.png">
<img src="captures/img_9.png">
<img src="captures/img_10.png">

<h1>config service  </h1>
<img src="captures/img_12.png">
<img src="captures/img_13.png">
<img src="captures/img_14.png">
<img src="captures/img_15.png">
<img src="captures/img_16.png">
<img src="captures/img_17.png">
<img src="captures/img_18.png">
<img src="captures/img_19.png">
<img src="captures/img_20.png">
<img src="captures/img_21.png">







<h3> ❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤❤ </h3>







