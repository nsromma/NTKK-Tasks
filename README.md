# NGH-Tasks
Interview tasks for NGH Oyj
Explanation of choice of various services used in this task

This assignment involves deploying a containerized nginx image to a production environment of my choice. I decided to choose AWS as my cloud provider. AWS has different services/products that helps easy, faster and safe deploying of applications. The second reason for choosing AWS is that I have a substantial knowledge of mmost of their services and I am more confident using their services.
For a containerized application, some of the services available to me in AWS include, Elastic Container Service (ECS), Elastic Kubernetes Service (EKS), Amazon Lambda, AWS LightSail, AWS AppRunner, EC2, AWS Fargate, etc. Of all these services, I decided to choose EC2 with an installed docker container to deploy my nginx conatinerized image. Comparatively, EC2 is much slower in deploying applications since it require configuring each of it's underlying services and dependencies in order to function properly. These configurations and its subsequent maintenance has the tendency to slow the deploying process. Configuring, maintaining and patching of these underlying services may also be costly. For a managed service like AwS Lambda, AWS LightSail, etc, the patching, maintenance of the underlying services are managed by the service provider. Security has also been an issue associated with EC2. Despite these setbacks, EC2 provides a highly flexible infrastructure for deploying one's application. With EC2, one can customized the underlying resources needed to manage and provision the infrastructure. You can customized, for e.g, the memory, os, vCPU, etc. of your EC2 depending on the type of application you are deploying. 
In the health sector, where data management and security, data privacy is on high alert, the EC2 instances can be configured in a private subnet and also using a VPN. In addition, you can configure a security group for each of your instances and determine the ip addresses that can access your instances. 
