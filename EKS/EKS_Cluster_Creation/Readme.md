## Create an EKS cluster with 2 nodes & instance type - t2.micro
    'eksctl create cluster \
    --name my-cluster \
    --region eu-central-1 \
    --nodegroup-name my-nodes \
    --node-type t2.micro \
    --nodes 2'

## Check created nodes
    'kubectl get nodes' 
    
## Check Default pods
    'kubectl get pods -n kube-system' or 'kubectl get po'
    
## Run a httpd service in pod
     'kubectl run <name_for_pod> <image_name>
        'kubectl run httpd --image=httpd'

## Delete Cluster
    'kubectl delete cluster <cluser_name> <cluster_region>'
