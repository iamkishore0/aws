## Amazon Machine Image
    An Amazon Machine Image is a special type of virtual appliance that is used to create a virtual machine within the Amazon Elastic Compute Cloud. It     serves as the basic unit of deployment for services delivered using EC2

## Creating AMI from an Instance

## Go to AWS management console and go to Instances and select an Instance that you want to create an AMI from it

![ss1](https://user-images.githubusercontent.com/98376417/187023284-cf0d217f-e46e-4f43-b684-3f8ff72763e2.png)


## Now click on Actions then Click on image and Click on Create Image
![s2](https://user-images.githubusercontent.com/98376417/187023291-7b46ab32-356e-4a21-b10a-99b42ae50c32.png)


## Now fill the details 'Image name' and 'Image description' as your desired name (my image) and click on Create Image
![s3](https://user-images.githubusercontent.com/98376417/187023296-07ae4b09-5ee1-4894-9fd8-7e0d1bdb7f12.png)


## Now you will see 'Create Image Request Received'
![s4](https://user-images.githubusercontent.com/98376417/187023300-fdf4ab6a-79bc-499e-83b7-2d26d486dedd.png)


## Now Click on AMI, which is left side and wait for a 5 to 10 minutes
![s5](https://user-images.githubusercontent.com/98376417/187023305-84ef4d84-a974-483b-93ae-5f72ebf419d3.png)


## After sometime AMI status will be changes from pending to Available
![s6](https://user-images.githubusercontent.com/98376417/187023311-d5b74c8a-2b6a-457c-8ec2-e437fac32ef5.png)


## Now select the image and go to Actions and click on launch
![s7](https://user-images.githubusercontent.com/98376417/187023319-b1d5d1cd-5254-40f1-9a0e-89e947edb671.png)


## Now launch an instance from our own/customized image by following instance creating process
![s8](https://user-images.githubusercontent.com/98376417/187023321-36c37958-fa7d-4c3f-886a-1dfaac787138.png)
