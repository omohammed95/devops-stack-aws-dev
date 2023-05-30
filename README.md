# devops-stack-test-aws-cluster

Repository that holds the Terraform files for my test cluster on AWS EKS using Camptocamp's [DevOps Stack](https://devops-stack.io/).

```bash
# Command to create the cluster
summon terraform init && summon terraform apply

# Command to get the kubeconfig settings for the created cluster
summon aws eks update-kubeconfig --name gh-v1-cluster --region eu-west-1

# Command to destroy the cluster
git@github.com:omohammed95/devpos-stack-module-jaeger.git
```
