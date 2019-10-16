# AMAZON WEB SERVICES (AWS)

## What is AWS
  * AWS is secure cloud services platform providing:
          - Computer power
          - Database storage
          - Content delivery
          - Many other functionalities to help businesses scale and grow

### Elastic Compute Cloud (EC2)
-> These are the virtual machines within the cloud on which you the OS level control.
-> You can run whatever you want in them

---------------------------------

## Helpful bash commands

### mv (move)
-> the rm command allows you to move files from one place to another
eg:
mv provision app

### rm (remove)
-> the rm command allows you to remove files
eg:
rm provision.sh

### ssh (secure shell)
-> This is quite a common task for Linux system administrators, when it is needed to execute some command or a local Bash script from a one Linux workstation or a server on another remote Linux machine over SSH
eg:
ssh -i ~/.ssh/LBA-kp.pem ubuntu@ec2-3-8-209-116.eu-west-2.compute.amazonaws.com

### scp (secure cp(copy))
-> scp stands for secure cp (copy), which means you can copy files across ssh connection. That connection will be securely encrypted, it is a very secure way to copy files between computers.
eg:
scp -i ~/.ssh/LBA-kp.pem provision.sh ubuntu@ec2-3-8-209-116.eu-west-2.compute.amazonaws.com:/home/ubuntu
