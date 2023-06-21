# Pre-requisites:

- Basic knowledge of Git and Github.
- Basic knowledge of AWS VPC and EC2 instances or have used other cloud services like Azure and GCP.
- Basic knowledge of shell commands.

# Intro
![](./images/Overview.png)

In this 3-part project series I learnt:

- How to work with cloud infrastructures like AWS VPC and EC2 instances with Terraform.
- How to install and config Git, Python and Docker in the two EC2 instances with Ansible.
- How to create a CI/CD pipeline that deploys your application automatically to the EC2 instances when there’s a new push/merge in the main branch of your Github.

It consist of three mini-projects. In each mini-project I used a different tool

# DevOps Mini-Project (Part 1): IaC with Terraform

Terraform is developed by a company called HashiCorp in order to manage infrastructures.

- Unify the view of resources using infrastructure as code.
- Support the modern data center(Iaas, Paas, SaaS).
- Expose a way for individuals and teams to safely and predictably change infrastructure.
- Provide a workflow that is technology agnostic.
- Manage anything with an API.

The code can be found in the feature/Terraform branch

# DevOps Mini-Project (Part 2): Introduction to Ansible

Ansible is powerful IT administration tool which is easy to learn and use. It can:

- Provision resources.
- Manage large amount of VM to a cluster.
- Delivery software to multiple node at same time.
- Run management script on multiple target systems.

The code can be found in the feature/Ansible branch

# DevOps Mini-Project (Part 3): CI/CD with Github Action

CI/CD stands for continuous integration and continuous delivery/deployment and it usually consists of 4 stages: code merge, test, build and deployment.

Github Action is a tool to automate the CI/CD workflows of developers.

- A free tool.
- serverless.
- easy to setup and manage.
