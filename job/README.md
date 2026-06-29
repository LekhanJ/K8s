# Job

We can use commands to manage jobs:
```bash
kubectl create job my-job --image=busybox
kubectl get jobs
kubectl delete job my-job
```

Or we can create a YAML file with kind:Job.

To use the YAML file:
```bash
kubectl apply -f job.yml
```