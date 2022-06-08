# Conversao temperatura - Kubedev
Projeto iniciativa devops

## Requirements
- docker
- k3d
- kubectl

## Starting environment
k3d cluster create meucluster --servers 3 --agents 3 -p "30000:30000@loadbalancer"
cd k8s
kubectl apply -f deployment.yaml
