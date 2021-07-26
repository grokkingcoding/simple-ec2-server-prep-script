### How to use the script? 

1. head over to AWS and launch an ec2 instance (e.g. Amazon Linux 2 )
2. Go to the UserData section of the ec2 instance setup 
3. copy and paste everything contained in ec2-server-script.sh into the UserData section
4. launch your ec2 instance 

Once your ec2 instance is launched, you can ssh into your server and check if docker and docker-compose have been installed, 

You can run the following commands to check if they have been installed properly: 

- docker version
- docker-compose version