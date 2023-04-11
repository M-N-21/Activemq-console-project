# Activemq-console-project

Ce projet Console est une application Java qui implémente un producteur et un consommateur pour le système de messagerie Apache ActiveMQ.

## Arborescence des dossiers

Le projet est organisé en deux dossiers principaux :

* `producteur`: Contient les sources Java pour le producteur de messages.
* `consommateur`: Contient les sources Java pour le consommateur de messages.

## Configuration

Avant d'exécuter le producteur et le consommateur, vous devez configurer le serveur ActiveMQ en modifiant le fichier `activemq.xml`. Vous pouvez trouver des instructions pour la configuration d'ActiveMQ dans la documentation officielle.

Assurez-vous que le serveur ActiveMQ est en cours d'exécution avant d'exécuter le producteur et le consommateur.

## Utilisation

Il faut d'abord faire un run producteur avant de faire un run du consommateur.


## Dépendances

Le projet utilise les dépendances suivantes :

* `javax.jms-api`: Fournit l'API Java Message Service pour les clients.
* `org.apache.activemq:activemq-all`: Fournit le client pour le système de messagerie Apache ActiveMQ.
* `org.slf4j:slf4j-simple`: Fournit le journalisation pour l'application.

Ces dépendances sont gérées par Maven et sont incluses dans le fichier `pom.xml`.

## Contribution

Les contributions sont les bienvenues! N'hésitez pas à ouvrir une pull request pour apporter des modifications à ce projet.

