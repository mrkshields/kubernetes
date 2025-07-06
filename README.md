# kubernetes
Home kubernetes setup

## Bootstrap

1. `kubectl create ns argocd`
2. `kubectl apply -n argocd -f argocd/argocd.yaml`
3. Setup ArgoCD
4. `kubectl apply -n argocd prod.yaml`
