
# :classical_building: Architecture

Here is the Architecture:
![](https://github.com/mohsin-786/Voting-App-Kubernetes/blob/main/lol.gif)



# :open_book: About this Voting App

This Project runs a Voting web-app using Kubernetes Deployments and Services.

It uses Redis and Postgres as Database & Python and NodeJS for Frontend.


## :inbox_tray: Installation

To run in local machine using Minikube

Install Minikube Kubectl and Docker

For Arch-Based:

-  Use an AUR helper like yay or paru

```bash
yay -Syu minikube kubectl docker
```
- Secondly
```bash
  sudo systemctl start docker
  sudo usermod -aG docker $USER
```    
- Lastly
```bash
  minikube start --kubernetes-version=latest
```

 For other distributions, you can install Docker and Kubectl using your package manager.
 
 And for Minikube do the following:


```bash
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube
minikube start --kubernetes-version=latest

```
## :cloud: Deployment

To deploy this project run the below command for each file:

```bash
  kubectl apply -f <filename>
```
Or,

Put all the files in one folder and run:
```bash
  kubectl apply -f <folder>
```


