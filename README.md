# About
How to setup Mac with developer tools

# Homebrew
Important: the logged-in user needs to have Administrative privileges.

1. Go [here](https://brew.sh/) and follow instructions
1. Verify installation with command `brew --version`
1. You will also have Git `git --version`

# NVM
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
