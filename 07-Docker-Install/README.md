# Installing Docker


  56 sudo apt update

  57 sudo apt install apt-transport-https ca-certificates curl software-properties-common

  58 curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

  59 sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"

  60 apt-cache policy docker-ce

  61 sudo apt install docker-ce

  62 docker ps

  63 usermod -a -G docker jenkins 

  64 systemctl restart jenkins


# Install Docker Compose

 106 sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

 107 sudo chmod +x /usr/local/bin/docker-compose

 108 docker-compose version 
