## Check helm repo list
    
    helm repo list
    
## Add stable repo to helm list
    
    helm repo add stable https://charts.helm.sh/stable
    
## Search all the charts from stable repo
    
    helm search repo stable
    
## Search for particular package

    helm search repo <package_name>  eg: helm search repo mysql, helm search repo nginx

## Pull a helm package for modification
    
    helm pull <package_name>
    
## untar downloaded package
    
    untar -xvzf <package_name>
    
## pack the modified package 
 
    helm package <folder_name>
