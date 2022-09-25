## Deploy a simple application
     ''kubectl create deployment <deployment_name> --image=<docker_image_name> --port=<port_number> --replicas=<number_of_replicas>'

   nginx deployment with 2 replicas/replica will create 2 pods at port 80
     
     'kubectl create deployment nginx-server --image=nginx --port=80 --replicas=2'
     
## Check Deployments
    
     'kubectl get deployments' or 'kubectl get deploy'
     
## Check Replicas
    
     'kubectl get replicaset'
     
## Check nodes
    
     'kubectl get nodes'
     
## Check pods

     'kubectl get po'
     
     
## Expose deployment to external network

     'kubectl expose deployment <deployment_name> --port=<port_number> --type=<deployment_type>
     
  expose nginx deployment
  
      'kubectl expose deployment nginx-server --port=80 --type=LoadBalancer'
