# AWS Projects Portfolio

![AWS IAM User Group Console Screenshot](/kubernetes-may2023/aws-project-aws-eks-via-nodegroup/misc/Console-IAM-UserGroup.png) | ![AWS VPC Screenshot](/kubernetes-may2023/aws-project-aws-eks-via-nodegroup/misc/Console-VPC.png) | ![AWS EKS Screenshot](/kubernetes-may2023/aws-project-aws-eks-via-nodegroup/misc/Wonderful-Metal-Mongoose.png)
# Cloud clusters minimal setups

## AWS EKS
- Core concepts to be aware about are
  - [Amazon EKS (Elastic Kubernetes Service)](https://docs.aws.amazon.com/cli/latest/reference/eks/index.html)
  - [Amazon Elastic Compute Cloud (EC2) - CLI reference docs for this](https://docs.aws.amazon.com/cli/latest/reference/ec2/)
  - [Amazon Virtual Private Cloud (VPC)](https://docs.aws.amazon.com/vpc/latest/mirroring/what-is-traffic-mirroring.html)
  - [AWS Identity and Access Management (IAM)](https://docs.aws.amazon.com/rolesanywhere/latest/userguide/introduction.html)

- The project is structured in the following way:
  - `README.md` - this file
  - `YAML/` - contains the CloudFormation YAML files used to create the VPC and Node Group for our EKS cluster.
  - `misc/` - contains screenshots and other miscellaneous files related to the project.
