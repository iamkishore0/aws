## Access EKS_Cluster Remotely

## Create a .kube directory in remote server and create config file 
      
      mkdir .kube && touch config
      
## Login to kuberneters_cluster server and copy content in .kube/config file
       
         cat .kube/config
         
## Paste the copied content in remote_server's config file


## Now ping kubernetes_cluster from Remote server
  Make sure you have installed Helm charts
  
        helm list
