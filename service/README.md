# Service

We can use commands like to manage persistent services:
```bash
kubectl get svc
kubectl get endpoints
kubectl create service <service-type> <service-name> --tcp=<port>:<target-port>
kubectl delete svc <service-name>
```

Or we can write a YAML file with kind:Service.

To use the YAML file:
```bash
kubectl apply -f service.yaml
```
