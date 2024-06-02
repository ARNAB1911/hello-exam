#!/bin/bash
apt-get update
apt-get install -y nginx
systemctl start nginx
systemctl enable nginx
apt-get install -y git
curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -
apt-get install -y nodejs
git clone <github repository cloning link>
cd Repo
npm install
node index.js





 git init 
	- git add . 
	- git commit -m “<your massage here>” 
	- git remote add <remote> https://<username>:<token>@github.com/<username>/<repo>.git 
	- git push -u <remote> <branch>
