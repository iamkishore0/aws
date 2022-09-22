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
    'kubectl get pods -n kube-system'
