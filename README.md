# About
How to setup Mac with developer tools

# Homebrew
Important: the logged-in user needs to have Administrative privileges.

1. Go [here](https://brew.sh/) and follow instructions
1. Verify installation with command `brew --version`
1. You will also have Git `git --version`

# Node
Node Version Manager (NVM) is an important too for [Node.js](https://github.com/nodejs/node) development. It allows you to swith between multiple versions of Node.js
1. Go [here](https://github.com/creationix/nvm) and follow instructions
1. Verify installation with command: `nvm --version`
1. Use NVM to display the available versions to install: `nvm ls-remote --lts`
1. Use NVM to install based on LTS name: `nvm install --lts=LTS_NAME_HERE`. Installations can also be done to a specific version: `nvm install vX.YY.Z`
1. Use NVM to use a specific version: `nvm use vX.YY.Z`
1. 

# GitHub
1. Create GitHub Account
1. Follow [these](https://help.github.com/categories/bootcamp/) instructions
1. If you have Multi-Factor Authencation (MFA), then HTTPS authentication will not work. Instead create [SSH keys](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/) or [personal access token](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/).

# Ruby
1. Install [Ruby Version Manager (RVM)](https://rvm.io/rvm/install)
    * Install: `\curl -sSL https://get.rvm.io | bash`
    * Post-install: `source /Users/kompseye/.rvm/scripts/rvm`
    * Install a version: `rvm install 2.7.0`
    * Use a version: `rvm use 2.7.0`
    * Add docs: `Ruby was built without documentation, to build it run: rvm docs generate-ri`
1. Use Interactive Ruby Shell (irb)
    * `rvm ls`
    * `puts "hello world"`
    * `exit`
    
# Java
Nowadays there is the Oracle Java Development Kit (JDK) and Open JDK. Read more [here](https://medium.com/@chamikakasun/how-to-manage-multiple-java-version-in-macos-e5421345f6d0).
1. Install Java Version Manager (jenv): `brew install jenv`
1. Follow instructions to update your shell configuration file
1. Install Maven: `brew install maven`
1. Install Java: 
    * `brew tap adoptopenjdk/openjdk`
    * `brew cask install adoptopenjdk13`
1. Verify Maven: `mvn --version`
1. Verify Java: `java --version`
1. Verify Java Compiler: `javac --version`

Brew installation problem?
```
cd /usr/local/Homebrew
git fetch --tags
git checkout 2.6.2 
```
Go back a version, see notes [here](https://github.com/ansible-collections/community.general/issues/1524#issuecomment-749226927)
