### This is Helm chart and Dockerfile to build custom Grafaтa image and deploy it to GKE within TeamCity.

##### Create rolebinding for default TeamCity service account in GKE to be able to deploy app in your cluster. 
##### Run the command:
kubectl create clusterrolebinding teamcity-cluster-admin-binding --clusterrole cluster-admin --serviceaccount=teamcity:default
