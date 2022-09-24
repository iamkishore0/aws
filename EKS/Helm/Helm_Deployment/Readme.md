## Pull a helm package
    
    helm pull package name
    
## Deploy/install pulled package
     
     helm install <name_for_deployment> <pulled_package_name>

## Direct Install without pulling
   
     helm install <name_for_deployment> <full_package_name_in_repo_list>
     
## Check helm list 

    helm list
    
## Check pods
 
   kubectl get pods
   
## Check services

   kubectl get svc
   
## Check Volumes

   kubectl get pvc
   
## Check config maps
   
   kubectl get config maps
   
## Uninstall deployment

   helm uninstall <Deployment_name>
