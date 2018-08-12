# kubernetes-1
Deploying a simple app to a pod and creating a service. 

This is a simple kubernetes app which deploys a pod with a Docker image kkeshavamurthy/alpine-nginx using the pod1.yaml file.
A NodePort service is created for the pods to be exposed on port 30001 using the pod1-service.yaml file. 

Commands to run
- kubectl create -f pod-1.yaml
- kubectl create -f pod1-service.yaml
