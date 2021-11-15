instilizing th docker environment(need copy ->paste ->exe manuely) 
curl -L https://github.com/docker/compose/releases/download/1.28.5/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose

`chmod +x /usr/local/bin/docker-compose`{{execute}}

fetch app from git hub
`git clone https://github.com/Lam-Weidong/foodorderingapp`{{execute}}

go to the correct directory
`cd /root/foodorderingapp/foodorderingapp_a`{{execute}}

run the program
`docker-compose up`{{execute}}


