# Purpose
Repository to track state of environment configuration


## Prerequsities

- kubectl
- minikube

All tools have difference related to platform.

# Minikube

minikube start

## Instal ArgoCD

kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml

### Forward ArgoCD Dashboard 

kubectl port-forward svc/argocd-server -n argocd 8080:443

## Add environment related configuration into Argo CD

### Project

### GitOps repository

### Project
