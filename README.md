# Amigos-API

RAILS APP

follow the steps for installation

## Installation
```bash
sudo apt install curl
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list

sudo apt-get update
sudo apt-get install git-core zlib1g-dev build-essential libssl-dev 
sudo apt-get install libreadline-dev libyaml-dev libsqlite3-dev sqlite3 
sudo apt-get install libxml2-dev libxslt1-dev libcurl4-openssl-dev software-properties-common libffi-dev nodejs yarn
```

## Ruby and Bundler Installation
```bash
cd
git clone https://github.com/rbenv/rbenv.git ~/.rbenv
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init -)"' >> ~/.bashrc
exec $SHELL

git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build
echo 'export PATH="$HOME/.rbenv/plugins/ruby-build/bin:$PATH"' >> ~/.bashrc
exec $SHELL

rbenv install 2.7.2
rbenv global 2.7.2
ruby -v
gem install bundler
```

inside the terminal go to a directory where you want to have the project
example steps:- 

  1- open a new terminal.

  2- ```cd /Documents ```
 
  3- ```git clone git@github.com:Amrzohdi/amigos-api.git ```

  4- ```cd amigos-api```
  
  5- ``` bundle instlall ``` 


# Reference

[ruby installation](https://gorails.com/setup/ubuntu/20.10)
