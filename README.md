# Astar-final-assessment-new
This is prerequisite for Final Assessment

Please follow the below steps to setup the inital environment

# To install Kong Ingress Controller with Helm 3

`$ helm repo add kong https://charts.konghq.com`

`$ helm repo update`

`$ helm install kong/kong --generate-name --set ingressController.installCRDs=false`

# To Create Deployments and Ingress
`kubectl apply -f .\customerdeploy.yaml -f .\ingress.yaml`

# To run RabbitMQ
`kubectl apply -f .\rabbitmqdeploy.yaml`

# To run Metrics Server
`kubectl apply -f .\metrics-server.yaml`

# To make your editing better
Use Visual Studio 2019/2022 for Development 

Use Visual Studio Code for editing with following Plugins:

1) Docker 
2) Kubernetes
3) Live Server (for HTML)

Tips

1) The JS code that needs to be edited is in `js` folder named `common.js` 
2) For tasks UI you can update the `script.js`
2) Try to complete maximum number of tasks

# To login to the application use the following users

1) Regular User

username: `johndoe`

password: `John$Doe`

2) Admin User

username: `admin`

password: `admin`

> To debug anything on Javascript please use the browser console on Chrome or Microsoft Edge or Firefox


> Wish you good luck!