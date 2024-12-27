# Projet EUL (Usine Logicielle e.SNCF)

## Contexte de la mission
Le projet EUL vise à mettre en place une plateforme de livraison continue centralisée pour les développements e.SNCF. Cette plateforme sert à orchestrer les pipelines CI/CD et à unifier les pratiques, qu'elles soient déployées sur Cloud (Azure) ou sur une infrastructure On-Premise.

---

## Enjeux
- Créer une infrastructure performante et évolutive pour soutenir les équipes de développement.
- Assurer l'intégration fluide des services Cloud et On-Premise.
- Mettre en place une stratégie robuste de reprise après sinistre (PRA).
- Optimiser le monitoring pour garantir une disponibilité continue.

---

## Tâches réalisées
### Création et configuration
- Déploiement de ressources Kubernetes (AKS) sur Azure.
- Mise en œuvre de la réplication des données entre Azure et AWS dans le cadre de la stratégie PRA.
- Restauration de volumes NetApp pour les environnements critiques.

### Automatisation et pipelines
- Développement et mise à jour de pipelines CI/CD sous Jenkins.
- Intégration de blocs d’exposition pour des services spécifiques de l’usine logicielle.

### Monitoring et optimisation
- Mise en place du monitoring via Datadog pour garantir la visibilité sur les ressources critiques.
- Résolution proactive d'incidents en temps réel grâce aux alertes configurées.

---

## Technologies utilisées
- **Cloud :** Azure (AKS, NetApp), AWS (S3, EC2).
- **CI/CD :** Jenkins, GitLab CI.
- **Monitoring :** Datadog, Prometheus.
- **Containerisation :** Docker, Kubernetes, Helm.

---

## Résultats et impact
- Réduction du temps de déploiement de 30% grâce à l'optimisation des pipelines.
- Garantie d'une haute disponibilité avec une stratégie PRA couvrant Azure et AWS.
- Simplification des processus grâce à une infrastructure unifiée pour Cloud et On-Premise.

---

## Retours clients
_"Mehdi a dépassé nos attentes en apportant une expertise technique et une capacité à résoudre les problèmes de manière proactive."_ – Chef de projet SNCF.

---

## Points forts du projet
- Environnement multi-cloud complexe.
- Contribution directe à la stratégie numérique de la SNCF.
