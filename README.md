# tp-hibernate
Dans ce repo vous allez trouver les solutions des exercices suivants:

- `H1`: l'exercice 1.
- `gestion_de_stock`: l'exercice 2.
- `gestion_de_projet`: l'exercice 3.
- `gestion_de_etat_civil`: le travail a faire 

## H1
Le projet H1 vise à créer une application de gestion de produits. Il comprend les fonctionnalités suivantes :

Création d'une entité Produit avec des annotations Hibernate.
Configuration de Hibernate via un fichier hibernate.cfg.xml.
Mise en place d'une classe HibernateUtil pour gérer la SessionFactory.
Création d'une interface IDao et d'une classe de service ProduitService.
Tests complets pour la création, la modification, la suppression et la recherche de produits.
Structure du Projet

### Structure
src/main/java/ma.projet.entity : Entité Produit.
src/main/java/ma.projet.config : Fichier de configuration Hibernate.
src/main/java/ma.projet.util : Classe HibernateUtil.
src/main/java/ma.projet.dao : Interface IDao.
src/main/java/ma.projet.service : Classe ProduitService.
src/test/java : Tests unitaires.

## Hiber2

### Objectif
Le projet Hiber2 vise à mettre en place une application de gestion de stock . Il comprend les fonctionnalités suivantes :

Création de classes entités pour les projets, les tâches et les employés avec des annotations Hibernate.
Configuration de Hibernate via un fichier hibernate.cfg.xml.
Mise en place d'une classe HibernateUtil pour gérer la SessionFactory.
Création d'une interface générique IDao et de classes de service (ProjetService, TacheService, EmployeService, EmployeTacheService).
Implémentation de diverses méthodes pour gérer les projets, les tâches et les employés.
Tests complets pour vérifier le bon fonctionnement des fonctionnalités.

### Conception
![gestion_de_stock](https://github.com/bananaacaat/tp-hibernate/assets/147453939/28730a9d-11e6-464d-a695-cbec0ca57ced)


## Hiber3

### Objectif
Le projet Hiber3 vise à mettre en place une application de gestion de projet. Il comprend les fonctionnalités suivantes :

Création de classes entités pour les projets, les tâches et les employés avec des annotations Hibernate.
Configuration de Hibernate via un fichier hibernate.cfg.xml.
Mise en place d'une classe HibernateUtil pour gérer la SessionFactory.
Création d'une interface générique IDao et de classes de service (ProjetService, TacheService, EmployeService, EmployeTacheService).
Implémentation de diverses méthodes pour gérer les projets, les tâches et les employés.
Tests complets pour vérifier le bon fonctionnement des fonctionnalités.

### Conception
![gestion_de_projet](https://github.com/bananaacaat/tp-hibernate/assets/147453939/b4b53f44-026d-4c73-9582-cc468b0b7fdb)



## TAR

### Objectif
Le projet Tar vise à développer une application de gestion de l'état civil des citoyens d'une province. Il inclut les entités Personne, Femme, Homme, et Mariage, ainsi que des fonctionnalités pour la gestion des données relatives à l'état civil.

### Conception
![gestion_de_etat_civil](https://github.com/bananaacaat/tp-hibernate/assets/147453939/f3269430-ad14-4ec5-8c60-9b438572414b)


## Comment Exécuter les Projets
Clonez ce référentiel sur votre ordinateur.
Configurez une base de données MySQL en conséquence (assurez-vous que les paramètres de base de données correspondent à ceux définis dans les fichiers de configuration Hibernate).
Importez les projets dans votre environnement de développement (par exemple, NetBeans).
Exécutez les projets individuellement en suivant les instructions spécifiques à chaque projet dans leurs répertoires respectifs.
Utilisez les tests unitaires pour vérifier le bon fonctionnement des fonctionnalités.
