## Deploy Wordpress 

## Step 1
       cat <<EOF >./kustomization.yaml
       secretGenerator:
       - name: mysql-pass
         literals:
         - password=YOUR_PASSWORD
       EOF
       
       
       
## Step 2
       curl -LO https://k8s.io/examples/application/wordpress/mysql-deployment.yaml

## Step 3
       curl -LO https://k8s.io/examples/application/wordpress/wordpress-deployment.yaml

## Step 4
       cat <<EOF >>./kustomization.yaml
       resources:
         - mysql-deployment.yaml
         - wordpress-deployment.yaml
       EOF
       
       
## Step 5
       kubectl apply -k ./
