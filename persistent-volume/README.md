# Persistent Volume

We can use commands like to manage persistent volumes:
```bash
kubectl get pv
kubectl delete pv <pv-name>
```

Or we can write a YAML file with kind:PersistentVolume.

To use the YAML file:
```bash
kubectl apply -f persistent-volume.yaml
```
