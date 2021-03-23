# Flask-App-with-mySQL-Data-Base-using-Docker-and-Kubernetes

steps :
- 1 - create a docker file to build our Flask App image by Docker
- 2 - create a secret resource to store the DB password (mySQL)
- 3 - create a persistent volume
- 4 - create a persistent volume claim
- 5 - create a deployment and service for mySQL server and create our table inside the container
- 6 - create a deployment, service and ingress to deploy our app on local Kubernetes cluster (Minikube)
- 7 - testing our services (get, create, update and delete users from our data base)
