# k8s
#MINIKUBE INSTALLATION
```
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube
minikube start
minikube start --driver=docker
sudo usermod -aG docker $USER
newgrp docker
sudo snap install kubectl

```

