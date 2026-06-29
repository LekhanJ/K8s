# DaemonSet

We can use commands to manage daemonsets:
```bash
kubectl get ds
kubectl delete daemonset <daemonset-name>
```

Or we can create a YAML file with kind:DaemonSet.

To use the YAML file:
```bash
kubectl apply -f daemon.yml
```