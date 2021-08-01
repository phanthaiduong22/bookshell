# Docker
- Remove all images:
`docker rmi $(docker images -a -q)`
#  K8s:
- Run k8s interactive mode:
`kubectl run -it --rm --image=mysql:5.6 --restart=Never mysql-client -- mysql -h mysql -ppassword`

