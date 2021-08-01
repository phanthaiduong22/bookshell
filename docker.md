# Docker
- Remove all images:
`docker rmi $(docker images -a -q)`
#  K8s:
- Run k8s interactive mode:
`kubectl exec --stdin --tty shell-demo -- /bin/bash`
- Get ip of minikube service:
`minikube service wordpress --url`
