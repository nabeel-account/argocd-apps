# These are argo applications

0-nginx-application.yaml: This is a single nginx applications

1-application.yaml: This is an app-of-app application. 
An app-of-app application is an ArgoCD application that points to other ArgoCD applications that point to the kubernetes manifest. 

An important feature of app-of-app is you only need to run this single ArgoCD application to deploy all other applications it references.

2-helm-metrics-server.yaml
Deploy a metrics server to retrieved cluster metrics