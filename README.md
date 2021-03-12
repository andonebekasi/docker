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



===================================================================
===================================================================

k8s metallb

kubectl apply -f https://raw.githubusercontent.com/google/metallb/v0.8.1/manifests/metallb.yaml



https://www.definit.co.uk/2019/08/lab-guide-kubernetes-load-balancer-and-ingress-with-metallb-and-contour/


https://blog.inkubate.io/install-and-configure-metallb-as-a-load-balancer-for-kubernetes/

============================================================================================================================


fix -- tested gcp gke
=====================


kubectl create deployment canda-app --image=andonebekasi/webasik


kubectl expose deployment canda-app --name=canda-app-service --type=LoadBalancer --port 8080 --target-port 80


https://cloud.google.com/kubernetes-engine/docs/tutorials/hello-app

https://kubernetes.io/docs/tutorials/stateless-application/expose-external-ip-address/ ====contoh 



https://kubernetes.io/docs/tasks/debug-application-cluster/get-shell-running-container/ --> akses shell pod


kubectl exec -i -t my-pod --container main-app -- /bin/bash




============================================================================================================================



kubernetes-dashboard


https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/


https://kubernetes.io/docs/tasks/access-application-cluster/port-forward-access-application-cluster/



https://phoenixnap.com/kb/kubectl-port-forward


https://www.edureka.co/community/31282/is-accessing-kubernetes-dashboard-remotely-possible

===========================================================================================================================



https://kubernetes.io/docs/tasks/access-application-cluster/service-access-application-cluster/


https://kubernetes.io/docs/tutorials/stateless-application/expose-external-ip-address/


https://unofficial-kubernetes.readthedocs.io/en/latest/tutorials/stateless-application/expose-external-ip-address/






===================================================================================================================================================




gcloud components install kubectl

add komponet di gcp

https://cloud.google.com/kubernetes-engine/docs/tutorials/hello-app





