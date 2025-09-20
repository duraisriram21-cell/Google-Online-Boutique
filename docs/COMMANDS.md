## Commands & Notes

Here are some commands I used while testing Online Boutique on EKS:

1. To create namespace:
   kubectl apply -f k8s/namespace.yaml

2. To apply manifests:
   kubectl apply -f k8s/kubernetes-manifests.yaml

3. To add ingress:
   kubectl apply -f k8s/online-boutique-ingress.yaml

4. To check pods:
   kubectl get pods -n <namespace>

5. To check services:
   kubectl get svc -n <namespace>

6. To describe ingress (for debugging):
   kubectl describe ingress -n <namespace>

