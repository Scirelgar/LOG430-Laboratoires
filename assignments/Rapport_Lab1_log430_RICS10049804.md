# Rapport – Laboratoire 1  
Nom :  
Code permanent :  
Cours : LOG430 – Architecture Logicielle Session Été 2025

## Informations générales  
URL du dépôt GitHub/GitLab :  
Langage utilisé :  
Base de données utilisée :  
ORM utilisé :

## Auto-évaluation par section

### Structuration du dépôt

| Éléments | Oui | Non | Commentaire / Justification |
| --- | --- | --- | --- |
| Le fichier README.md est présent et complet |  |  |  |
| Un fichier .gitignore pertinent est utilisé |  |  |  |
| Le dépôt présente une structure claire et logique |  |  |  |

### Application client

| Éléments | Oui | Non | Commentaire / Justification |
| --- | --- | --- | --- |
| Elle permet de rechercher, ajouter, consulter, retourner des produits |  |  |  |
| L’interface est claire et fonctionnelle |  |  |  |

### Persistance et ORM

| Éléments | Oui | Non | Commentaire / Justification |
| --- | --- | --- | --- |
| Un ORM est utilisé pour gérer la persistance |  |  |  |
| L’application accède correctement à la base de données |  |  |  |
| Les opérations de lecture et d’écriture sont persistées |  |  |  |
| La base de données est cohérente après plusieurs opérations concurrentes |  |  |  |
| L’utilisation des indexes dans la base de données est bien appliquée et justifiée |  |  |  |

### Justifications et documentation

| Éléments | Oui | Non | Commentaire / Justification |
| --- | --- | --- | --- |
| Au moins deux décisions architecturales (ADR) sont rédigées |  |  |  |
| Les choix technologiques sont documentés |  |  |  |
| Les diagrammes UML sont présents (classes, séquence, déploiement) |  |  |  |
| Les diagrammes sont faits avec un outil de diagramme comme code (PlantUML, Mermaid) |  |  |  |
| La documentation est écrite en Markdown |  |  |  |
| La documentation suit un gabarit comme Arc42 |  |  |  |
| La documentation est organisée dans un répertoire dédié (“docs”) |  |  |  |

### Conteneurisation et exécution

| Éléments | Oui | Non | Commentaire / Justification |
| --- | --- | --- | --- |
| L’application est conteneurisée avec un Dockerfile |  |  |  |
| Cliente est conteneurisée |  |  |  |
| La base de données instanciée manuellement |  |  |  |
| La base de données instanciée avec un système d’orchestration (ex. Docker Compose) |  |  |  |
| Les instructions d’exécution sont présentes dans le README |  |  |  |

### Intégration continue (CI/CD)

| Éléments | Oui | Non | Commentaire / Justification |
| --- | --- | --- | --- |
| Une pipeline CI/CD est configurée sur GitHub Actions ou GitLab CI |  |  |  |
| Le lint est fonctionnel |  |  |  |
| L’étape test unitaire est fonctionnelle |  |  |  |
| L’étape build Docker est fonctionnelle |  |  |  |
| L’image est publiée sur Docker Hub |  |  |  |

## Réflexion personnelle

**Quels sont les limitations du style d’architecture client/serveur à 2 couches (2-tier) ?**  
...

**Quelles sont les limites du mécanisme de base de données utilisée ? Quelles tactiques permettent d’augmenter la capacité de réponse (ex. réduire le temps de réponse, augmenter le nombre d’usagers simultanés) ?**  
...

**Dans le contexte du projet du laboratoire 1, quels sont les efforts techniques et risques liés à la migration d’un système de persistance relationnel vers NoSQL (ou inversement) ?**  
...

**Quels éléments vous ont posé le plus de difficulté ?**  
...

**Que souhaitez-vous améliorer pour les prochains laboratoires ?**  
...
