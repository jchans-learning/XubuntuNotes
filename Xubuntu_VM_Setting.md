# Setting Web Dev Enviornment for Xubuntu VM on Win 10

## Some Universal Tools

### Install Git

$ sudo apt install git

#### Config Git User

$ git config --global user.email "you@example.com"
$ git config --global user.name "Your Name"

### Install Vim

$ sudo apt install vim

### Install curl

$ sudo apt install curl

### Install zsh and oh-my-zsh
### Instructions from: https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH
### Instructions from: https://ohmyz.sh/#install

apt install zsh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"


## Install Web Dev Tools

### Install Node.js v14.x in Xubuntun
### Instructions from: https://github.com/nodesource/distributions/blob/master/README.md#debinstall

curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs

### Install Yarn

npm install -g yarn
