# Namespace

We can use commands like to manage namespaces:
```bash
kubectl get ns
kubectl create ns <namespace-name>
kubectl delete ns <namespace-name>
```

Or we can write a YAML file with kind:Namespace.

To use the YAML file:
```bash
kubectl apply -f <file-name.yml>
```
