**development enviorment setting**

* basic
  * ubuntu 18.04.5
  * virtualmachine

* curl
  * sudo apt-get update
  * sudo apt-get install curl
  * ! err-> sudo reboot
  * curl --version
  
* docker
  * sudo apt install docker.io docker-compose -y
  * docker version
  * docker-compose version
  * sudo apt-get install software-properties-common
  * sudo usermod -aG docker $USER
  * echo $USER
* node.js
  *sudo apt-get install build-essential libssl-dev -y
  * curl -OL https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install | bash
  * bash install.sh
  * source .profile
  * nvm install v8
  * node -v
  * npm -v
  
* go
  * curl -OL https://golang.org/dl/go1.12.17.linux-amd64.tar.gz
  * tar -xvf go1.12.17.linux-amd64.tar.gz
  * sudo mv go /usr/local
  * gedit .profile
    * add twolines in last
               * 
  