Project main goal is to deploy an application 2048 game in kubernetes cluster using ACR in Azure Devops.

#################################   prerequists ###############################################
1) Create azure devops subscription 
2) create azure service connection 
3) Create an azure container registry 
4) Create an Azure Kubernetes cluster. (Make sure you need to add to the ACR name as integration)

################################# Detailed Process ################################################
1) Azure devops >> repos >> import the repo's >> using githhub url.
2) Azure pipeline using azure repos with the help of stater pipeline.
3) Edit the pipeline as required like ( building of docker file, Acr logins, pusing the image to ACR) open the kube yml file
4) Now you can also add the kubectl commands to the script by using the existing yml file in azure repo then we can run 
5) we can edit pipline based triggers for the continues integrations
