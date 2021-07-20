# Kubernetes
Learning k8 with the image created in the docker tutorial repo docker-fastapi-mongo

Building my image into the docker inside the minikube vm
```bash
eval $(minikube docker-env)
docker build -t fastapi-mongo:1.0
```

Applying k8 configs, secrets. deploy-service
```bash
kubectl apply -f <NAME.yaml>
```

Reaching the service URL
```bash
minikube service <SERVICE>
```
