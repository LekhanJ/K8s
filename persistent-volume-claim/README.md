# Persistent Volume Claim

We can use commands like to manage persistent volume claims:
```bash
kubectl get pvc
kubectl delete pvc <pvc-name>
```

Or we can write a YAML file with kind:PersistentVolumeClaim.

To use the YAML file:
```bash
kubectl apply -f persistent-volume-claim.yaml
```
