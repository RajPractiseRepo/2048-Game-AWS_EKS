#Deploying the 2048-game on EKS and Fargate 🚀
The 2048 application is getting deployed on the EKS (manahging the control plane) and Fargate (managing the data source resources); using Ingress Resources to create the Ingress Controller which will provide the access to the 2048 application which is present in the POD;

It seems like you are interested in deploying via EKS so lets get started 🚀

#Installations / Commands to execute
1. Install all the prerequisites from the prerequsites.md
2. Run the steps from installing-eks.md
3. Run the steps from 2048-game-deploy-ingress.md
4. Run the commands from iam-oidc-connector.md
5. Run the commands from alb-controller-add-on.md

#Demo of the Deployemnt of the 2048 App Deploying 2048 Application on AWS EKS Cluster

2048 Application Running on EKS Cluster
![2048-Game](https://github.com/RajPractiseRepo/2048-Game-AWS_EKS/assets/148358152/af1083b2-d63b-4347-97fc-eb9a4d18b78c)
