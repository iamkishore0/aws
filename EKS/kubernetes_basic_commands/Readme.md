## Deploy a simple application
     ''kubectl create deployment <deployment_name> --image=<docker_image_name> --port=<port_number> --replicas=<number_of_replicas>'

   nginx deployment with 2 replicas/replica will create 2 pods at port 80
     
     'kubectl create deployment nginx-server --image=nginx --port=80 --replicas=2'
