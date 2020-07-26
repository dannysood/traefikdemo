kubectl apply -f https://raw.githubusercontent.com/containous/traefik/v1.7/examples/k8s/kubectl taint nodes --all node-role.kubernetes.io/master--rbac.yaml


to expose port outside minikube
`minikube tunnel`
or
` minikube service <servicename> --url`
