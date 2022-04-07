## How to run

### Creating a local cluster using k3d
Create a cluster with 3 servers and 3 agents
```
k3d cluster create mycluster --servers 3 --agents 3
```

### Listing clusters
```
k3d cluster list
```

### Creating naked pods
Create the pods described in pod.yaml
```
kubectl apply -f pod.yaml
```

### Listing pods

```
kubectl get pods
```

### Deleting pods

```
kubectl delete pod mypod mypod-label
```

### Deleting cluster

```
k3d cluster delete mycluster
```
