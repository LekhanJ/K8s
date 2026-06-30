# CronJob

We can use commands to manage cronjobs:
```bash
kubectl create cronjob my-cron --image=busybox --schedule="*/5 * * * *" -- echo "Hello"
kubectl get cronjob
kubectl delete cronjob my-cron
```

Or we can create a YAML file with kind:CronJob.

To use the YAML file:
```bash
kubectl apply -f cron.yml
```