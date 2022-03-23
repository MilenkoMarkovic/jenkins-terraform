# terraform-ansible-jenkins
The end result of this project is Terraform code that creates an AWS environment with public subnets and EC2 instance(s) with an Ansible Playbook that installs Docker on the newly created EC2 instance(s). When the code is pushed to a GitHub repo a GitHub Webhook will trigger a Jenkins CI/CD Pipeline that will execute a series of actions depending on whether we are pushing code to the dev or main branch.


Full write up: https://troy-ingram.medium.com/three-best-friends-terraform-ansible-and-jenkins-828285dcf8b
