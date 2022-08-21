
## Create EC2 Instance 

'Login to AWS Management Console' click on 'Services' which is on the top left

Search for 'EC2' in the search tab and click on 'EC2 - Virtual servers in the cloud'

Now click on 'instances' - which is at left side

Click on 'Launch instances' - which is at top left

Fill the required details as below

    Name and Tags >> Name : Myfirstserver
    Application and OS Images (Amazon Machine Image)
        Search of OS name 'centos 7' and select centos 7
    Instance type : t2.micro
    Key pair (login)
        Click on create a new keypair 
           Enter keypair name: mykeypair
           Key pair type: RSA
           Private key file format: .ppk
        Click on Create key pair
    Network settings
        Select 'ssh traffic from: Anywhere'
    Configure storage
        Default values
Click on 'Launch Instance' - Which is at Mid right side
