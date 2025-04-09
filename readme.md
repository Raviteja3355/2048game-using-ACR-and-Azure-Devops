Project main goal is to deploy an application 2048 game in kubernetes cluster using ACR in Azure Devops.

#################################   prerequists ###############################################
Create azure devops subscription 
create azure service connection 
Create an azure container registry 
Create an Azure Kubernetes cluster. (Make sure you need to add to the ACR name as integration)

################################# Detailed Process ################################################
Azure devops >> repos >> import the repo's >> using githhub url.
Azure pipeline using azure repos with the help of stater pipeline.
Edit the pipeline as required like ( building of docker file, Acr logins, pusing the image to ACR) open the kube yml file
Now you can also add the kubectl commands to the script by using the existing yml file in azure repo then we can run 
we can edit pipline based triggers for the continues integrations