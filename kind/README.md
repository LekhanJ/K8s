# KIND Cluster

```
Create the cluster using the configuration file:

```bash

kind create cluster --config kind-config.yaml --name my-kind-cluster
```
Verify the cluster:

```bash

kubectl get nodes
kubectl cluster-info
```
## 3. Accessing the Cluster
Use kubectl to interact with the cluster:
```bash

kubectl cluster-info
```
