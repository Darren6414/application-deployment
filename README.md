# application-deployment

# ☸️ Dépôt de Déploiement GitOps (ArgoCD)

Ce dépôt est l'infrastructure en tant que code (IaC) de notre projet MLOps de l'ENSAE. Il applique les principes du **GitOps** pour séparer le code applicatif du code d'infrastructure.

Il contient l'ensemble des manifests Kubernetes (Deployment, Service, Ingress) nécessaires pour faire tourner notre API sur le cluster Kubernetes du **Datalab SSPCloud**. Ce dépôt est surveillé en temps réel par **ArgoCD**, qui se charge d'appliquer automatiquement toute modification d'architecture ou de version d'image Docker.

🛠️ **Technologies :** Kubernetes, ArgoCD, YAML, SSPCloud.
🔗 **Code Applicatif :** [Mettre le lien vers l'autre repo ici]
