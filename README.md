# As we are going to automate everything, we are gonna automate building the infrastructure through terraform

# We are gonna split the infrastructure into pieces , we are gonna write a teraform code snippets for the following services:
  * Vpc including internet gateways,subnets and routing tables
  * codepipeline and codebuild
  * S3 bucket
  * EKS cluster
  * security groups
  * ECR

# after running our first "terraform apply" we have to share the .tfstate files
 so to keep the idempotency shared
# Cloudflare free tier to manage the domain records,limit the access based on GeoIp and security features
