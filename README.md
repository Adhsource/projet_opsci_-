# projet_opsci_-

# Introduction
Bonjour,

Je vous présente le projet OPSCI, qui vise à améliorer l'architecture d'un projet initial en y intégrant des éléments événementiels. L'objectif principal est de créer un système robuste capable d'intégrer de grandes quantités de données provenant de différentes sources avec une grande résilience aux erreurs.

# Prérequis
Avant de démarrer le projet, quelques prérequis doivent être pris en compte :

Utilisation du docker-compose fourni;

# Architecture
Le projet utilise un message broker Kafka pour faciliter l'intégration des données. Nous avons opté pour cette solution en raison de sa capacité à gérer de grandes quantités de données avec une haute disponibilité et une faible latence.

# Détails techniques
## Kafka
Nous utilisons Docker (ou Kubernetes) pour lancer Kafka, avec plusieurs topics spécifiques :

product : pour la création de nouveaux produits en masse.
event : pour la création d'événements.
stock : pour la gestion des mouvements de stocks.
error : pour la gestion des erreurs.

Consommateurs et Producteurs
Nous fournissons des consommateurs et des producteurs pour les différents éléments, disponibles sous forme d'images Docker ou de dépôts GitHub. Il est important de bien configurer les variables d'environnement pour assurer le bon fonctionnement de chaque composant.

# Conclusion
Je vous remercie de votre attention et je reste à votre disposition pour toute question ou demande de clarification concernant le projet OPSCI et son architecture événementielle.

Cordialement,