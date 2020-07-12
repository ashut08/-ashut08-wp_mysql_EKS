# Amazon-EKS

Hii All !!
In this project, I have lunched a crash proof rescalable Ghost Architecture on Amazon EKS. Ghost is a famous open source blogging platform used widely by independent journalists & writers across the globe.

# What is Amazon EKS ?

Amazon Elastic Kubernetes Service (Amazon EKS) is a fully managed Kubernetes service. Customers such as Intel, Snap, Intuit, GoDaddy, and Autodesk trust EKS to run their most sensitive and mission critical applications because of its security, reliability, and scalability.

EKS is the best place to run Kubernetes for several reasons. First, you can choose to run your EKS clusters using AWS Fargate, which is serverless compute for containers. Fargate removes the need to provision and manage servers, lets you specify and pay for resources per application, and improves security through application isolation by design. Second, EKS is deeply integrated with services such as Amazon CloudWatch, Auto Scaling Groups, AWS Identity and Access Management (IAM), and Amazon Virtual Private Cloud (VPC), providing you a seamless experience to monitor, scale, and load-balance your applications. Third, EKS integrates with AWS App Mesh and provides a Kubernetes native experience to consume service mesh features and bring rich observability, traffic controls and security features to applications. Additionally, EKS provides a scalable and highly-available control plane that runs across multiple availability zones to eliminate a single point of failure.
# Creating cluster using eksctl command from cluster.yml file
![Screenshot from 2020-07-12 08-07-15](https://user-images.githubusercontent.com/49301530/87242064-f11a2a00-c446-11ea-9a84-b57e55cf9bd2.png)
### run kustomization.yml file using command
   <b>kubectl create -k .  </b>
### Get all detail of pods
 ![Screenshot from 2020-07-12 10-52-01](https://user-images.githubusercontent.com/49301530/87242130-83bac900-c447-11ea-9277-772615e8777d.png)
### With help of external ip of cluster install wordpress

![Screenshot from 2020-07-12 10-51-54](https://user-images.githubusercontent.com/49301530/87242141-a6e57880-c447-11ea-927f-f4b9aa068845.png)
![Screenshot from 2020-07-12 10-54-08](https://user-images.githubusercontent.com/49301530/87242142-a9e06900-c447-11ea-8a40-70546852ec3e.png)
![Screenshot from 2020-07-12 10-54-25](https://user-images.githubusercontent.com/49301530/87242148-b238a400-c447-11ea-9b0c-1691c18129e7.png)

### wow ! we succesfully install wordpress
![Screenshot from 2020-07-12 10-54-54](https://user-images.githubusercontent.com/49301530/87242173-f461e580-c447-11ea-8495-6a1481051ac1.png)

