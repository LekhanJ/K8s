# Pod

We can use commands to manage pods
```bash
kubectl run <pod-name> --image=<container-name>
kubectl get pods
kubectl delete pod <pod-name>
```

With namespace:
```bash
kubectl run <pod-name> --image=<container-name> -n <namespace-name>
kubectl get pods -n <namespace-name>
kubectl delete pod <pod-name> -n <namespace-name>
kubectl delete pods --all -n <namespace-name>
```

Or we can create a YAML file with kind:Pod.

To use the YAML file:
```bash
kubectl apply -f pod.yml
```