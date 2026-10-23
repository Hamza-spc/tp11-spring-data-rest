# TP 11 : Spring Data REST

Application Spring Boot `ms-banque` exposant automatiquement les repositories JPA `Compte` et `Client` comme ressources REST HATEOAS sous le chemin de base `/api` (base de données H2 en mémoire), avec projections, pagination, tri, recherche par type et navigation des relations.

## 1. Structure du projet et configuration

![Structure du projet et configuration](screenshots/01-structure-config.png)

## 2. Entités JPA : Compte, Client et TypeCompte

![Entités JPA](screenshots/02-entites-jpa.png)

## 3. Repositories Spring Data REST et projections

![Repositories et projections](screenshots/03-repositories-projections.png)

## 4. Initialisation des données et exposition des identifiants

![Initialisation des données](screenshots/04-initialisation-donnees.png)

## 5. Exécution : HAL, projections, pagination et recherche

![Exécution](screenshots/05-execution.png)
