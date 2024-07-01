# docker-swarm-HA

Installation:
* https://github.com/JamesTurland/JimsGarage/blob/main/Docker-Swarm/swarm.sh

glusterfs fix for mount:
* https://stanislas.blog/2018/10/how-to-mount-local-glusterfs-volume-boot-fstab-systemd-fix/
* https://serverfault.com/questions/800494/glusterfs-mount-on-boot-on-clustered-servers-rhel-7

Config:
* https://blog.antosubash.com/posts/part-2-setup-docker-swarm-with-traefik-and-portainer **Traefik Network**
* https://github.com/ChristianLempa/boilerplates/blob/main/docker-compose/traefik/config/traefik.yaml **Traefik Yaml (Doesn't Work)**

Let's Encrypt:
* https://doc.traefik.io/traefik/https/acme/#providers
* https://go-acme.github.io/lego/dns/porkbun/
* https://doc.traefik.io/traefik/user-guides/docker-compose/acme-dns/#prerequisite

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
