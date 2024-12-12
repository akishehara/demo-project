# demo-project


GCP Concepts & Networking

3/5 Part - 

1,2,3 questions - Answer - https://github.com/akishehara/demo-project.git

4th question - 

Explain how you configure the deployment through ArgoCD.

* First, I installed argocd on the Kubernetes cluster by applying the installation manifests. Then, I connected the git repo that got the K8s manifest to argcd, specifying where the application should be deployed.Then, I synced it with the cluster to deploy the microservice.  
