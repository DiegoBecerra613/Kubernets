Comandos para iniciar los kubernets

minikube start

kubectl apply -f deployment.yaml

kubectl apply -f service.yaml

kubectl apply -f namespace.yaml

kubectl get pods

kubectl get services

minikube service my-api-service --url
