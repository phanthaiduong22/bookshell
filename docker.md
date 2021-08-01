# Docker
- Remove all images:
`docker rmi $(docker images -a -q)`
#  K8s:
- Run k8s's pod interactive mode:
`kubectl exec --stdin --tty <pod-name> -- /bin/bash`
- Get ip of minikube service:
`minikube service wordpress --url`
- Get secrets
`kubectl get secrets`
