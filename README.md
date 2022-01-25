# Cloud-1

# Docker
- [Openclassroom](https://openclassrooms.com/fr/courses/2035766-optimisez-votre-deploiement-en-creant-des-conteneurs-avec-docker/6211517-creez-votre-premier-dockerfile)
- [Nginx Docker](https://hub.docker.com/_/nginx/)
- [Doc PHPMyAdmin](https://github.com/phpmyadmin/docker/blob/master/README.md)

```
docker exec -it <id> bash
```

## Run playbook
```
ansible-playbook playbook.yml -i hosts
```

## Reset all
```
docker stop $(docker ps -q)
```
```
docker stop $(docker ps -q); docker rm MySQL  Nginx  PHPMyAdmin  Wordpress ; rm -rf /root/*; echo y | ufw reset
```

## Install ansible
```
pip3 install --user ansible
```
```
ansible-galaxy collection install community.docker
```