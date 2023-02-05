# Altschool-Terraform-Project
craeting an Application load balancer, Ec2 instances, and an A record on Route53 using terraform. 

### creating a vpc using terraform 

![project-vpc](https://user-images.githubusercontent.com/102290896/216829560-36e2e681-ccfc-4b16-b82f-df0e48c011cc.jpeg)


### Creating the Internet gateway 

![VPC-IGW](https://user-images.githubusercontent.com/102290896/216829524-d551be9a-5e76-4fb3-a0b2-94dc115dc0cc.png)


### creating Subnet Route Tables

![Project-route-tables](https://user-images.githubusercontent.com/102290896/216829467-c2bb0b9b-ff26-48c7-8359-36136f9bd615.png)

### Creating subnets 

![vpc-subnets](https://user-images.githubusercontent.com/102290896/216829637-951d2d23-bbf7-4f1f-8d52-c49455b92a9c.png)

### creating Network ACL

![Network ACL](https://user-images.githubusercontent.com/102290896/216829683-8c8b2465-2811-40d4-829e-cfe38dddf47f.png)

### Creating a security group for the load balancer

![LB-SG](https://user-images.githubusercontent.com/102290896/216829834-ed5b6ebb-b5a5-442f-864c-be8b5264894e.jpeg)

### Creating security groups to allow SSH, HTTP, and, HTTPS ports 

![SG to allow ports 22, 80,   443](https://user-images.githubusercontent.com/102290896/216829953-2688c539-d200-48fb-af79-8f83a28014a4.png)

### Creating 3 Ec2 instances 

![Ec2 instances](https://user-images.githubusercontent.com/102290896/216830015-4597c542-2c61-4e27-8b61-54072e04f108.jpeg)

### Creating the Application load balancer

![project-lb](https://user-images.githubusercontent.com/102290896/216830097-c7402a14-1e46-408b-8b02-d26a2757a3a9.jpeg)

### Creating and attaching the target groups to the loadd balancer 

![Target-group](https://user-images.githubusercontent.com/102290896/216830214-6ee762c7-ddb7-489a-9c69-324324fe8661.jpeg)

### craeting hosted zone

![hosted-zone ](https://user-images.githubusercontent.com/102290896/216830475-940382a8-cc91-4cf1-936d-a520905e1f0a.png)

### A records created by terraform 

![A records ](https://user-images.githubusercontent.com/102290896/216830674-b82cb260-5f68-47ad-b452-fd00c182a8f3.png)























