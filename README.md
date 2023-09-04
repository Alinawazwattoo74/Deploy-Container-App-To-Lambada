# Deploy-Container-App-To-Lambada
In this project we deploy our app to lambda a server less service of aws.
i also share my history and the errors i face during accessing the aws cli and lambda
ubuntu@ip-172-31-33-166:~$ history
    1  sudo apt-get update -y
    2  sudo apt install docker.io -y
    3  sudo systemctl status docker
    4  ls
    5  git clone https://github.com/Alinawazwattoo74/Deploy-Container-App-To-Lambada.git
    6  ls
    7  cd Deploy-Container-App-To-Lambada/
    8  ls
    9  sudo docker build . -t hello-app:v1.0.0
   10  docker images
   11  sudo docker images
   12  ls
   13  cd Deploy-Container-App-To-Lambada/
   14  ls
   15  sudo aws ecr get-login-password --region ap-south-1 | docker login --username AWS --password-stdin 468883803657.dkr.ecr.ap-south-1.amazonaws.com
   16  sudo docker tag hello-app:latest 468883803657.dkr.ecr.ap-south-1.amazonaws.com/hello-app:latest
   17  docker images
   18  sudo docker images
   19  sudo su
   20  sudo apt-get install awscli
   21  aws configure
   22  aws configure
   23  sudo aws ecr get-login-password --region ap-south-1 | docker login --username AWS --password-stdin 468883803657.dkr.ecr.ap-south-1.amazonaws.com
   24  aws configure
   25  sudo aws ecr get-login-password --region ap-south-1 | docker login --username AWS --password-stdin 468883803657.dkr.ecr.ap-south-1.amazonaws.com
   26  aws configure list
   27  sudo aws --profile default ecr get-login-password --region ap-south-1 | docker login --username AWS --password-stdin 468883803657.dkr.ecr.ap-south-1.amazonaws.com
   28  /usr/local/bin/aws --profile default ecr get-login-password --region ap-south-1 | docker login --username AWS --password-stdin 468883803657.dkr.ecr.ap-south-1.amazonaws.com
   29  which aws
   30  /usr/bin/aws --profile default ecr get-login-password --region ap-south-1 | docker login --username AWS --password-stdin 468883803657.dkr.ecr.ap-south-1.amazonaws.com
   31  sudo /usr/bin/aws --profile default ecr get-login-password --region ap-south-1 | docker login --username AWS --password-stdin 468883803657.dkr.ecr.ap-south-1.amazonaws.com
   32  sudo usermod -aG docker $USER
   33  sudo /usr/bin/aws --profile default ecr get-login-password --region ap-south-1 | docker login --username AWS --password-stdin 468883803657.dkr.ecr.ap-south-1.amazonaws.com
   34  sudo reboot
   35  history
