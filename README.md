# Linux_CQRE

* sudo add-apt-repository ppa:git-core/ppa
* sudo apt-get update
* sudo apt-get install git-core
* git version
* git config --global user.name "leeyesol"
* git config --global user.email "jackey6493@naver.com"
* git config --global push.default "simple"
* cd ~/
* mkdir ~/linuxrepo.git
* cd linuxrepo.git
* mkdir study1
* cd study1
* git init
* git status
* vi helloworld.c
* git add helloworld.c
* git commit -m "Sentence Output 'Hello World' used 'printf function'"
* git remote add origin https://github.com/leeyesol/Linux_CQRE.git
* git push origin master
* git pull origin master
* git fetch --all
* git reset --hard origin/master
* git commit -m "Sentence Output Modification : 'Hello Linux!' used 'printf function'"
