### Start Cluster
minikube start --nodes 4
### Apply changes
kubectl apply --filename deployment.yaml
### Start Service
minikube service hedge-doc