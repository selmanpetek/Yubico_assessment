# IaC for a trivial web application

## Checklist

**_If you don't have a ready environment to deploy this IaC. Please deploy the link first._**

**For creating new VPC, Subnets, and etc.**
- https://docs.aws.amazon.com/codebuild/latest/userguide/cloudformation-vpc-template.html

**Assuming that you already have an environment where you can spin up your EC2 instances.**
- Create a web server.
- Create a database server.
- Create a bastion host.
- Open their communication port on the security groups.

## Release

**Adjust the aws command with your variables, and then run it for having this Infrastructre in your AWS account.**

```sh
aws cloudformation create-stack --stack-name <value> --parameters <value>
```
