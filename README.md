kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl apply -f ingress.yaml

sudo vim /etc/hosts
add this line below to file above
<minikube ip> static.local

To get the minikube ip
Do this command   
minikube ip
