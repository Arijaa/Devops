# Projet CI/CD pour une Application Spring Boot

Ce projet vise à mettre en place un pipeline CI/CD (Continuous Integration/Continuous Deployment) pour une application Spring Boot. L'objectif est d'automatiser le processus de développement, de test, de qualité et de déploiement de l'application, en utilisant des outils tels que Jenkins, SonarQube, Nexus, Docker, DockerHub, Postman/Swagger, Grafana et Prometheus.

## Architecture de la Solution

L'architecture de la solution comprend plusieurs composants interconnectés :

1. **Tests Unitaires avec Mocks**: Les tests unitaires sont implémentés avec l'utilisation de mocks pour isoler les différentes parties du code et garantir des tests indépendants et cohérents.

2. **Pipeline Jenkins**: Un script automatisé est configuré dans Jenkins pour gérer les différentes étapes du processus de CI/CD. Cela inclut la récupération du code depuis Git, la compilation du projet, l'exécution des tests unitaires avec JUnit, l'analyse de la qualité du code avec SonarQube, la préparation et la distribution de la version, ainsi que le déploiement des images Docker.

3. **Correction des Problèmes Sonar**: Les problèmes de qualité de code identifiés par SonarQube sont corrigés dans le cadre du pipeline CI/CD pour garantir des normes élevées de qualité et de maintenabilité du code.

4. **Tests d'Intégration avec Postman/Swagger**: Les services de l'application sont testés à l'aide de Postman ou Swagger, en effectuant des opérations simples comme l'ajout d'un élément suivi d'une requête GET pour vérifier le bon fonctionnement de l'API.

5. **Supervision avec Grafana et Prometheus**: Les différents conteneurs de l'application sont supervisés en temps réel à l'aide de Grafana et Prometheus, permettant une surveillance proactive de la performance et de la disponibilité de l'application.

## Comment Utiliser ce Projet

1. Cloner le projet depuis Git.
2. Configurer Jenkins pour exécuter le pipeline CI/CD en se référant au fichier de configuration Jenkinsfile.
3. Suivre les résultats du pipeline dans Jenkins pour surveiller le processus de développement, de test et de déploiement.
4. Corriger les problèmes identifiés par SonarQube dans le code source.
5. Tester les services de l'application à l'aide de Postman ou Swagger en ajoutant des éléments et en vérifiant les réponses.
6. Utiliser Grafana et Prometheus pour surveiller les performances des conteneurs de l'application en temps réel.

Ce projet fournit une infrastructure robuste pour automatiser le processus de développement et de déploiement d'une application Spring Boot, améliorant ainsi l'efficacité du développement logiciel et la qualité du produit final.

# Technologies Utilisées



<div align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jenkins/jenkins-original.svg" alt="Jenkins" width="100"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sonarqube/sonarqube-original.svg" alt="SonarQube" width="100"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nexus/nexus-original-wordmark.svg" alt="Nexus" width="100"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" width="100"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postman/postman-original.svg" alt="Postman" width="100"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/grafana/grafana-original.svg" alt="Grafana" width="100"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/prometheus/prometheus-original.svg" alt="Prometheus" width="100"/>
</div>

