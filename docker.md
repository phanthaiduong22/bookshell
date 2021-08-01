# Docker
- Remove all images:
`docker rmi $(docker images -a -q)`
- Run container interactive mode:
`docker exec -it ubuntu_bash bash`
#  K8s:
- Run k8s's pod interactive mode:
`kubectl exec --stdin --tty <pod-name> -- /bin/bash`
- Get ip of minikube service:
`minikube service wordpress --url`
- Get secrets
`kubectl get secrets`
