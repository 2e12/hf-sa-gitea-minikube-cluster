### Start Cluster
```
minikube start --nodes 3
```
### Apply changes
```
kubectl apply --filename deployment.yaml
```
### Start Service
```
minikube service gitea
```