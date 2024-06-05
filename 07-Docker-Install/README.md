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
