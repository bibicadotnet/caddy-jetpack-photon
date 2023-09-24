# caddy-jetpack-photon


mkdir /root/caddy
cd /root/caddy
docker network create caddy

wget https://raw.githubusercontent.com/bibicadotnet/caddy-jetpack-photon/main/docker-compose.yml

docker-compose up -d --build --remove-orphans --force-recreate
