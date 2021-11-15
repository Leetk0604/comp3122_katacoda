curl -L https://github.com/docker/compose/releases/download/1.28.5/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose

chmod +x /usr/local/bin/docker-compose

git clone https://github.com/Lam-Weidong/foodorderingapp

cd /root/foodorderingapp/foodorderingapp_a

docker-compose up

