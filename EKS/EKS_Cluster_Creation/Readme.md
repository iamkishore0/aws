## Create an EKS cluster with 2 nodes & instance type - t2.micro
    eksctl create cluster \
    --name my-cluster \
    --region eu-central-1 \
    --nodegroup-name my-nodes \
    --node-type t2.micro \
    --nodes 2

