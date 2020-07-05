# aws_bation
to make vpc into the aws

1. make dir name aws_bation 
2. go into aws_bation (cd aws_bation)
3. add file project_aws.yml
4. add role aws_bation (ansible-galaxy init aws_bation)
5. add var.yml into aws_bation/ dir


how to run playbook project_aws.yml

`ansible-playbook project.yml -i inventory -e var.yml