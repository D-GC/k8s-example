# k8s-example
Simple k8s deployment example with docker, minikube

## start minikube with docker driver:
`minikube start --driver=docker`

## Start minkube dashboard:
`minikube dashboard`

## Deploy app:
`kubectl apply -f k8s/`

## Check service name: 
`kubectl get services`

## This will open up a browser window that serves your app and shows the app's response:
`minikube service my-app-service`

## Debug
`kubectl get pods --selector=app=my-app`

## Check pod logs:
`kubectl logs -l app=my-app`

`kubectl logs -l my-app-pod-name`


[Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)

