# This is a very simple python client.

# Several changes are needed for you to use it against the events API:
# You should create the Dockerfile that:

1. Uses a Python3 base image
1. Installs all the necessary dependencies
1. Runs the flask application inside gunicorn
  

python3 --version
apt-get update 
sudo apt-get -y install python3-pip
pip3 --version
pip3 install -r requirement.txt
python3 app.py


http://34.105.75.10:5000/


Kubernetes: troubleshooting ingress and services traffic flows
https://medium.com/@ManagedKube/kubernetes-troubleshooting-ingress-and-services-traffic-flows-547ea867b120

Internet ←-> AWS ELB ←-> k8s ingress ←-> k8s service ←-> k8s pods

kubectl logs PODNAME
kubectl describe service SERVICENAME

# sample-pythonclient-master
