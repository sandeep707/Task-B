# We are going to deploy the task of 1 with Kubernetes deployment file over here.

**#BACKEND # KANBAN-APP**
We will build the kanban-app Dockerfile with below command:

docker build -t backend .  # Tagging it as backend

Created app-deployment.yaml for deploying the kanban-app

kubectl apply -f node-deployment.yaml  # To create this deployment, just run this command

Created app-service.yaml for deploying service of kanban-app

kubectl apply -f node-service.yaml # To Create the service use this command

**#Front End # KANBAN-UI**

Same process as above and it also have 2 files one for service and one for deployment


# DATABASE # POSTGRES

Same process as BACKEND and it also have 2 files one for service and one for deployment
