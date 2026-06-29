# Deployment

We can use commands to manage deployments:
```bash
kubectl create deployment <name> --image=<image>
kubectl get deployments
kubectl scale deployment <deployment-name> --replicas=<number>
kubectl delete deployment <deployment-name>
```

Or we can create a YAML file with kind:Deployment.

To use the YAML file:
```bash
kubectl apply -f deploy.yml
```