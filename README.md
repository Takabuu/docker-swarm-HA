# docker-swarm-HA

Installation:
* https://github.com/JamesTurland/JimsGarage/blob/main/Docker-Swarm/swarm.sh

glusterfs fix for mount:
* https://stanislas.blog/2018/10/how-to-mount-local-glusterfs-volume-boot-fstab-systemd-fix/

Config:
* https://blog.antosubash.com/posts/part-2-setup-docker-swarm-with-traefik-and-portainer
* https://github.com/ChristianLempa/boilerplates/blob/main/docker-compose/traefik/config/traefik.yaml

containers:
* https://github.com/lhns/docker-swarm-keepalived

mesh network:
* https://docs.docker.com/engine/swarm/ingress/
* https://stackoverflow.com/questions/69600893/docker-swarm-routing-mesh

settings for docker compose traefik:
* https://doc.traefik.io/traefik/reference/static-configuration/cli/

deploying portainer:
```sh
docker stack deploy -c portainer-agent-stack.yml portainer
```
