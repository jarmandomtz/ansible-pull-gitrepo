# ansible-pull code
This is central repo for ansible-pull command on AWS

## Examples
gitrepo: ansible-book-repo

- ansible-pull: installation of ansible-pull executing ansible commands manually
  - path: ansible-book-repo/exercises/ansible-pullmode
- ansible-pull_cloudformation: Use of UserData for install prerequisites, execute ansible roles and configure crontab for ansible-pull
  - path: ansible-book-repo/exercises/ansible-pull_cloudformation

## Playbooks
- helloworld: Playbook for create an AppServer for deploy nodeJS app
  - path: ./helloworld.yaml
- jenkins: Creation of jenkins master for execute CI, CD pipelines
  - path: ./jenkins.yaml

## Jenkins role

Reference,
- https://archives.jenkins-ci.org/redhat-stable/
- https://aws.amazon.com/es/blogs/compute/executing-ansible-playbooks-in-your-amazon-ec2-image-builder-pipeline/
- https://pkg.jenkins.io/redhat-stable/
- https://www.jenkins.io/doc/tutorials/tutorial-for-installing-jenkins-on-AWS/
