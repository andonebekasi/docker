# docker



https://hub.docker.com/u/andonebekasi

==================


docker build -t andonebekasi/tahubaso .

docker run -d --name asikasik -p 80:80 andonebekasi/tahubaso










============


k8s

============


kubectl create deployment tahubaso --image=andonebekasi/webasik

kubectl get deployments

kubectl describe deployment nginx




# Describe commands with verbose output

kubectl describe nodes my-node

kubectl describe pods my-pod




==============================================


Exposing Your Nginx Service to Public Network

=============================================

kubectl create service nodeport nginx --tcp=80:80

kubectl get svc



 Clean Up
==============


$ kubectl delete deployment my-app

$ kubectl delete svc my-app


