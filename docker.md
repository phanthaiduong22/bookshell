# Linux
- Kill port:
`fuser -n tcp -k 9001 `
# Docker
- Remove all images:
- `docker rmi $(docker images -a -q)`
- Remove all container:
- `docker rm -f $(docker ps -a -q)`
- Run container interactive mode:
- `docker exec -it ubuntu_bash bash`
- Remove all volume:
- `docker volume rm $(docker volume ls -q)`
#  K8s:
- Run k8s's pod interactive mode:
`kubectl exec --stdin --tty <pod-name> -- /bin/bash`
- Get ip of minikube service:
`minikube service wordpress --url`
- Get secrets
`kubectl get secrets`
