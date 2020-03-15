# docker

andonebekasi/webasik

https://hub.docker.com/u/andonebekasi









============
k8s

============


kubectl create deployment nginx --image=nginx

kubectl get deployments

kubectl describe deployment nginx



Exposing Your Nginx Service to Public Network
=============================================

kubectl create service nodeport nginx --tcp=80:80

kubectl get svc



 Clean Up
==============


$ kubectl delete deployment my-app

$ kubectl delete svc my-app


