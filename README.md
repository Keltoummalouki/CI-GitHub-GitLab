# CI/CD Practice Project – GitHub Actions & GitLab CI

## 🎯 Objectif du projet

Ce projet a été créé dans le cadre d’un **live coding** pour pratiquer et comprendre la **CI/CD** à travers deux outils majeurs :

- **GitHub Actions**
- **GitLab CI**

Il sert de support pédagogique pour configurer, exécuter et faire évoluer des pipelines d’intégration continue.

---

## 📚 Objectifs pédagogiques

À l’issue de ce projet, vous serez capable de :

- Comprendre les concepts d’**Intégration Continue (CI)**, **Livraison Continue (CD)** et **Déploiement Continu**
- Expliquer les **avantages d’un pipeline CI/CD**
- Comprendre les concepts de base de **GitHub Actions**
- Créer un **workflow CI simple avec GitHub Actions**
- Comprendre les concepts de base de **GitLab CI**
- Écrire un **`.gitlab-ci.yml` minimal** et l’étendre progressivement

---

## 🔁 Rappels CI / CD

- **CI – Intégration Continue**  
  Automatisation des tests et validations à chaque changement de code.

- **CD – Livraison Continue**  
  Le code est toujours prêt à être déployé.

- **Déploiement Continu**  
  Chaque changement validé est automatiquement déployé en production.

---

## ✅ Pourquoi utiliser un pipeline CI/CD ?

- Détection rapide des bugs
- Amélioration de la qualité du code
- Automatisation des tâches répétitives
- Déploiements fiables et reproductibles
- Gain de temps pour les équipes

---

## 🛠️ Outils et technologies

- Git
- GitHub Actions
- GitLab CI
- Application de démonstration simple (selon le live coding)

---

## 🚀 GitHub Actions

### Concepts clés

- **Workflow** : automatisation définie en YAML
- **Events** : événements déclencheurs (`push`, `pull_request`, etc.)
- **Jobs** : groupes de tâches
- **Steps** : étapes d’un job
- **Actions** : briques réutilisables

### Emplacement des workflows

```text
.github/workflows/
````

### Objectif du workflow CI

* Déclenché sur un `push`
* Installation des dépendances
* Exécution des tests
* Vérification du build

---

## 🦊 GitLab CI

### Concepts clés

* **Pipeline**
* **Stages**
* **Jobs**
* **Runners**
* **Artifacts**
* **Cache**

### Fichier principal

```text
.gitlab-ci.yml
```

### Pipeline minimal

* `install`
* `test`
* `build`

Le pipeline sera enrichi progressivement durant le live coding.

---

## 📂 Structure du projet (exemple)

```text
.
├── .github/
│   └── workflows/
│       └── ci.yml
├── .gitlab-ci.yml
├── src/
├── tests/
├── README.md
```

---

## 🧪 Live Coding – Étapes prévues

1. Création d’un pipeline CI simple
2. Ajout de jobs et de stages
3. Gestion des artifacts
4. Mise en cache des dépendances
5. Comparaison GitHub Actions vs GitLab CI

---

## 📚 Ressources utiles

* GitHub Actions : [https://docs.github.com/actions](https://docs.github.com/actions)
* GitLab CI : [https://docs.gitlab.com/ee/ci/](https://docs.gitlab.com/ee/ci/)
* CI Explained : [https://martinfowler.com/articles/continuousIntegration.html](https://martinfowler.com/articles/continuousIntegration.html)

---

## 👨‍💻 Auteur

Projet créé dans un objectif de **formation, veille technologique et pratique CI/CD**.
