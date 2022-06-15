# Keycloack-postgres-kubernetes-deployment
YAML deployment files for keayclock &amp; postgres


1- clone the repo and go into directory

2- Kubectl apply -f postgres.yaml

3- kubectl apply -f keycload-deployment.yaml

Forward the port from Pod service

kubectl port-foward <service_name> external_port:internal_service_port
