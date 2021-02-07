# Setting Web Dev Enviornment for Xubuntu VM on Win 10

## Some Universal Tools

### Setting Fireforx Preference

- Startup with previous session.

### Install Git

```
$ sudo apt install git
```

#### Config Git User

```
$ git config --global user.email "you@example.com"
$ git config --global user.name "Your Name"

# credential helper TBD
git config --global credential.helper 'cache --timeout 3600'
```



### Install Vim

```
$ sudo apt install vim
```

### Install curl

```
$ sudo apt install curl
```

### Install zsh and oh-my-zsh

- Instructions from: https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH
- Instructions from: https://ohmyz.sh/#install
- https://tecadmin.net/how-to-install-zsh-on-ubuntu-20-04/

```
$ apt install zsh
$ chsh -s $(which zsh)
$ sudo apt install git-core curl fonts-powerline
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

$ sudo vi ~/.zshrc 
# set ZSH_THEME="agnoster"

$ zsh
```

Terminal default geometry
- 120 col
- 36 row


#### Hide username and hostname

- https://www.programmersought.com/article/22513997246/
- Modify the .zshrc file add prompt_context() {} at the buttom of the file


```
prompt_context() {}

```



## Install Web Dev Tools

### Install Node.js v14.x in Xubuntun

- Instructions from: https://github.com/nodesource/distributions/blob/master/README.md#debinstall

```
$ curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
$ sudo apt-get install -y nodejs
```

### Install Yarn

```
$ sudo npm install -g yarn
```


npm install -g yarn
