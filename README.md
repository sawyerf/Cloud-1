# Cloud-1

# Docker
- [Openclassroom](https://openclassrooms.com/fr/courses/2035766-optimisez-votre-deploiement-en-creant-des-conteneurs-avec-docker/6211517-creez-votre-premier-dockerfile)
- [Nginx Docker](https://hub.docker.com/_/nginx/)
- [Doc PHPMyAdmin](https://github.com/phpmyadmin/docker/blob/master/README.md)
```
docker build -t nginx-site .
docker run -d -p 80:80 nginx-site
docker exec -it <id> bash
```

```
docker stop $(docker ps -q)
```

```
ansible-playbook playbook.yml -i hosts
```

```
docker stop $(docker ps -q); docker rm MySQL  Nginx  PHPMyAdmin  Wordpress ; rm -rf /root/*; echo y | ufw reset
```