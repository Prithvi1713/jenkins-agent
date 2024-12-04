
## Assignemnt 2 
### ansible production -m apt -a " update_cache=yes" -b
### f-> ansible production -m apt -a "name=openjdk-17-jdk state=present" -b
### g-> ansible production -m setup -a "filter=ansible_user,ansible_uptime,ansible_processor,ansible_mounts,ansible_memory_mb" -b
### h-> ansible-inventory --list
### i-> ansible production,development -m command -a "which git"
### , & :!

 ##  Assignment 5
 ### kubectl version --client
 ### minikube start
 ### kubectl get po -A
 ### kubectl create deployment hello-minikube --image=kicbase/echo-server:1.0
 ### kubectl expose deployment hello-minikube --type=NodePort --port=8080
 ### kubectl get services hello-minikube
 ### minikube service hello-minikube
 ### kubectl port-forward service/hello-minikube 7080:8080
 ### minikube config set memory 9001
 ### minikube stop
