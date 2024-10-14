Ce projet est une application Java développée sous NetBeans pour la gestion des produits dans un magasin. Il utilise Hibernate pour la persistance des données et MySQL comme base de données. L'application permet la création, la modification, la suppression et l'affichage de produits, avec des fonctionnalités supplémentaires telles que le filtrage par prix et la recherche de produits commandés entre deux dates.

Fonctionnalités
Ajouter des produits : Créer de nouveaux produits avec des détails comme le nom, le prix, etc.
Modifier des produits : Mettre à jour les informations d'un produit existant.
Supprimer des produits : Supprimer des produits de la base de données.
Afficher des produits : Visualiser la liste des produits, rechercher par ID ou selon des critères spécifiques.
Filtrer des produits : Afficher les produits dont le prix est supérieur à 100 DH.
Gestion des commandes : Afficher les produits commandés entre deux dates données.
Structure du Projet
Le projet est organisé en plusieurs packages pour une meilleure gestion du code :

ma.projet.entity : Contient l'entité Produit avec les annotations JPA pour représenter les produits.
ma.projet.dao : Contient l'interface générique IDao pour les opérations CRUD.
ma.projet.service : Contient la classe ProduitService qui implémente l'interface IDao et les méthodes spécifiques à la gestion des produits.
ma.projet.config : Contient le fichier de configuration Hibernate hibernate.cfg.xml.
ma.projet.util : Contient la classe utilitaire HibernateUtil pour gérer les sessions Hibernate.
ma.projet.test : Contient une classe de test pour vérifier les différentes fonctionnalités.
Prérequis
Java 8+
NetBeans (ou tout autre IDE compatible avec Maven)
MySQL (version 5.7+)
Hibernate-JPA pour la gestion de la persistance des données
Pilote JDBC MySQL pour connecter l'application à la base de données
