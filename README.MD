## Steps to provisison cluster using ArgoCD and helm and kubectl 
### nginx ingress controller and grafana



azure cli
```bash 
brew update && brew install azure-cli
az login
```

kubectl to query kubernetes api

brew install kubectl 


helm 

```bash
kubectl create namespace argocd 
kubectl apply -f https://raw.githubusercontent.com/argoproj/argo-cd/v1.0.2/manifests/install.yaml -n argocd
```