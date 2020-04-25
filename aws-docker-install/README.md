# Install docker

In this section we will go through the following steps
1. Create a free Tier AWS account
2. Create a key pair
3. Create an EC2 instance
4. SSH into the EC2 instance
5. Install docker

> Install Docker 
```shell
sudo yum update -y
sudo yum install docker
sudo systemctl start docker
sudo usermod -a -G docker ec2-user
# re-start machine
docker info
```
