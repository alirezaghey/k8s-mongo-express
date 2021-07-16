## kubectl apply commands in order

    kubectl apply -f mongodb-secret.yaml
    kubectl apply -f mongodb-deployment.yaml
    kubectl apply -f mongodb-configmap.yaml
    kubectl apply -f mongodb-express-deployment.yaml

## kubectl get commands

    kubectl get pod
    kubectl get pod --watch
    kubectl get pod -o wide
    kubectl get service
    kubectl get secret
    kubectl get all | grep mongodb

## kubectl debugging commands

    kubectl describe pod mongodb-deployment-xxxxxx
    kubectl describe service mongodb-service
    kubectl logs mongo-express-xxxxxx

## to access mongo express service on a minikube cluster

    minikube tunnel

[Read more](https://minikube.sigs.k8s.io/docs/handbook/accessing/)
