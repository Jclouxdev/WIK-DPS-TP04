```
kubectl plugin -h
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.43.0/deploy/static/provider/cloud/deploy.yaml
kubectl describe pods nomdupodingress
kubectl apply -f pod.yml
kubectl get pods -n ingress-nginx
kubectl port-forward service/podtest-service 3000:3000
```

Activer Ingress

```
kubectl addons ingress
```
