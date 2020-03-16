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




url

========================


https://www.tecmint.com/deploy-nginx-on-a-kubernetes-cluster/


https://kubernetes.github.io/ingress-nginx/deploy/baremetal/


https://github.com/kubernetes/ingress-nginx/blob/master/docs/troubleshooting.md


https://kubernetes.io/docs/reference/kubectl/cheatsheet/


https://codeburst.io/getting-started-with-kubernetes-deploy-a-docker-container-with-kubernetes-in-5-minutes-eb4be0e96370



https://www.tecmint.com/install-apache-web-server-in-a-docker-container/



https://knative.dev/v0.10-docs/serving/samples/hello-world/helloworld-php/




https://codingbee.net/tutorials/kubernetes/hello-world-pods




