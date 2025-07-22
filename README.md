# helm-charts-automation

Collection des Charts Helm Charts déstinés à l'orchestration et à l'automatisation de tâches.

## Airflow (airflow)

**Apache Airflow est un orchestrateur de workflows** open-source utilisé pour automatiser des processus complexes. Airflow permet de définir des pipelines sous forme de DAGs (Directed Acyclic Graphs), où chaque étape est un job (ou tâche) à exécuter. C’est un outil couramment utilisé pour orchestrer des tâches de data engineering et de machine learning.

- _Utilité_ : Orchestration de workflows complexes (exécution de tâches séquentielles et parallèles).
- _Cas d'usage_ : Traitement de données par lots, gestion des pipelines d'ETL, orchestration de tâches d'apprentissage automatique et gestion des dépendances entre tâches.

## Argilla (argilla)

**Argilla est une plateforme open-source pour la gestion de données et d'annotations liées à l'intelligence artificielle (IA)**, en particulier pour les tâches de traitement du langage naturel (NLP). Argilla permet de structurer et d'annoter des données pour les rendre prêtes pour l'entraînement des modèles de machine learning.

- _Utilité_ : Annotation et gestion des jeux de données pour l'apprentissage automatique et le traitement du langage naturel.
- _Cas d'usage_ : Préparer des datasets annotés pour entraîner des modèles de machine learning (principalement pour des applications NLP comme la classification de texte, l'analyse de sentiments, etc.).

## Argo CD (argo-cd)

**Argo CD est un outil GitOps pour Kubernetes, qui permet de déployer et de gérer les applications Kubernetes** en synchronisant l’état du cluster avec un dépôt Git. Il fournit une gestion continue des déploiements et permet de déployer des applications automatiquement à partir de fichiers de configuration stockés dans Git.

- _Utilité_ : Livraison continue (CD) avec une approche GitOps pour gérer les déploiements d'applications Kubernetes.
- _Cas d'usage_ : Déploiement automatisé d'applications sur Kubernetes en utilisant des fichiers de configuration Git.

## Argo Workflows (argo-workflows)

**Argo Workflows est un orchestrateur de workflows Kubernetes** qui permet de créer et d’exécuter des workflows complexes dans Kubernetes. Il permet d’orchestrer des étapes parallèles et séquentielles, et est particulièrement utilisé pour gérer des pipelines de données ou des workflows de machine learning.

- _Utilité_ : Orchestration de workflows complexes dans Kubernetes (exécution parallèle de tâches, gestion des dépendances).
- _Cas d'usage_ : Gestion des pipelines de données, orchestration de workflows ML, automatisation de l'exécution des tâches.

## Label Studio (label-studio)

**Label Studio est un outil open-source d'annotation de données qui permet de créer des annotations pour les modèles de machine learning**. Il prend en charge divers types de données comme le texte, l’image, l’audio, et permet de structurer des données pour entraîner des modèles.

- _Utilité_ : Création d’annotations sur des données pour entraîner des modèles ML.
- _Cas d'usage_ : Annotation de données pour des projets de machine learning, notamment pour les applications de classification, de segmentation d’image, ou de traitement du langage naturel.

## Metaflow (metaflow)

**Metaflow est un framework open-source développé par Netflix pour la gestion des pipelines de machine learning**. Il permet de créer, exécuter et surveiller des workflows ML, et offre une gestion simple des tâches parallèles et des dépendances.

- _Utilité_ : Gestion des workflows de machine learning (ML), suivi des versions des données et des modèles.
- _Cas d'usage_ : Orchestration de pipelines de machine learning, gestion de l’entraînement des modèles, et suivi de l’exécution des étapes de ML.

## MLflow (mlflow)

**MLflow est une plateforme open-source pour la gestion du cycle de vie des modèles de machine learning**. Elle inclut des outils pour suivre les expériences, gérer les modèles, et déployer des modèles en production.

- _Utilité_ : Gestion des expériences, suivi des modèles, et déploiement dans un environnement de production.
- _Cas d'usage_ : Suivi des expérimentations de machine learning, gestion des versions des modèles, et déploiement en production.

## Yatai (yatai)

**Yatai est une plateforme d'orchestration de modèles de machine learning** qui permet de gérer les versions de modèles et leur déploiement. C'est une plateforme qui simplifie le déploiement de modèles en production et leur gestion sur Kubernetes.

- _Utilité_ : Gestion du cycle de vie des modèles de machine learning et orchestration de leur déploiement.
- _Cas d'usage_ : Gestion de la mise en production et de la mise à jour continue des modèles de machine learning sur Kubernetes.
