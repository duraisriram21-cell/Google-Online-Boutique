# Online Boutique on EKS with Ingress

## Layout
- k8s/: Kubernetes manifests (namespace, services, deployments, ingress)
- helm/: Helm charts/values (if used)
- docs/: Screenshots and command logs

## Quick Start
kubectl apply -f k8s/namespace.yaml
kubectl apply -f k8s/kubernetes-manifests.yaml
kubectl apply -f k8s/online-boutique-ingress.yaml
