![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-black?style=for-the-badge&logo=sonarqube&logoColor=4E9BCD)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

# 🚀 MyCIApp

Projet personnel de Xavier Ropero pour la mise en place d'une chaîne complète CI/CD avec tests, qualité de code et déploiement Docker.

---

## 🧠 Objectif

Ce projet a pour but de démontrer la capacité à :
- Mettre en place une intégration continue (CI)
- Automatiser les tests et la qualité logicielle
- Déployer avec Docker
- Suivre des métriques via SonarCloud

---

## 🔍 SonarQube

https://sonarcloud.io/organizations/xavier-ropero/projects

### 📦 Front-end

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=MyCIApp-Front&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=MyCIApp-Front)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=MyCIApp-Front&metric=bugs)](https://sonarcloud.io/summary/new_code?id=MyCIApp-Front)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=MyCIApp-Front&metric=coverage)](https://sonarcloud.io/summary/new_code?id=MyCIApp-Front)
[![Duplicated Lines](https://sonarcloud.io/api/project_badges/measure?project=MyCIApp-Front&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=MyCIApp-Front)

### 🔧 Back-end

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=MyCIApp-Back&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=MyCIApp-Back)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=MyCIApp-Back&metric=bugs)](https://sonarcloud.io/summary/new_code?id=MyCIApp-Back)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=MyCIApp-Back&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=MyCIApp-Back)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=MyCIApp-Back&metric=coverage)](https://sonarcloud.io/summary/new_code?id=MyCIApp-Back)
[![Duplicated Lines](https://sonarcloud.io/api/project_badges/measure?project=MyCIApp-Back&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=MyCIApp-Back)

---

## 🐳 DockerHub

https://hub.docker.com/u/xavierropero

---

## ⚙️ Installation

### 📁 Cloner le projet

```bash
git clone https://github.com/xavierropero/mon-projet-ci-cd.git


# BobApp

Clone project:

> git clone XXXXX

## Front-end 

Go inside folder the front folder:

> cd front

Install dependencies:

> npm install

Launch Front-end:

> npm run start;

### Docker

Build the container:

> docker build -t bobapp-front .  

Start the container:

> docker run -p 8080:8080 --name bobapp-front -d bobapp-front

## Back-end

Go inside folder the back folder:

> cd back

Install dependencies:

> mvn clean install

Launch Back-end:

>  mvn spring-boot:run

Launch the tests:

> mvn clean install

### Docker

Build the container:

> docker build -t bobapp-back .  

Start the container:

> docker run -p 8080:8080 --name bobapp-back -d bobapp-back 



