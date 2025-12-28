

# Create
minikube start --driver=podman --container-runtime=containerd

# Start
podman machine start
kubectl run redis --image=redis123

# View
kubectl get nodes
kubectl describe pod myapp-pod

# Stop
minikube stop
podman machine stop


# Delete
kubectl delete deployment hello-minikube
kubectl delete service nginx



# Cli Apps
minikube
podman


# Desktop Apps
Podman Desktop
