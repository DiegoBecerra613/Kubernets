Comandos para iniciar los kubernets

minikube start

kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl apply -f namespace.yaml

kubectl get pods
kubectl get services

minikube service my-api-service --url

kubectl logs my-api-deployment-fb88bcff8-8ptbq
kubectl logs my-api-deployment-fb88bcff8-bftzv
kubectl logs my-api-deployment-fb88bcff8-p8hpr
kubectl logs my-api-deployment-fb88bcff8-q85kg
kubectl logs my-api-deployment-fb88bcff8-tgfxl
