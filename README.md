# packer-jenkins-server


Build an Jenkins server with latest AMI.
This packer project checkout the latest AMI and install following ansible package on it.

 - geerlingguy.jenkins
 - geerlingguy.ansible-role-packer
 - geerlingguy.ansible
 - dev-sec.ssh-hardening
 - dev-sec.os-hardening

The Jenkinsfile file will run 4 stages of creating packer.

Create Jenkins task, with pipeline project type and finally add this repository into the Jenkins tasks' SCM to run from git.


Jenkins is running on port 8080 and username: admin and password: admin.
