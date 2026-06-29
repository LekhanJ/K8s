# ReplicaSet

We can use commands to manage replicasets:
```bash
kubectl create -f replica.yml
kubectl get rs
kubectl scale --replicas=<number> rs/<replicaset-name>
kubectl delete rs <replicaset-name>
```

Or we can create a YAML file with kind:ReplicaSet.

To use the YAML file:
```bash
kubectl apply -f replica.yml
```