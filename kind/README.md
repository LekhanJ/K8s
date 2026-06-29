# KIND Cluster

Create the cluster using the configuration file:

```bash
kind create cluster --config kind-config.yaml --name my-kind-cluster
```

Verify the cluster:
```bash
kubectl get nodes
kubectl cluster-info
```

Use kubectl to interact with the cluster:
```bash
kubectl cluster-info
```
