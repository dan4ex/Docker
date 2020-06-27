# Deploy Jenkins production ready!

Requirements:
  - 1 GB+ of RAM
  - 50 GB+ of drive space
  - Docker
  - Docker-compose
  
### Starting
1. Edit **caddyfile** and change your domain and email
2. Edit environment **JAVA_OPTS** in docker-compose.yml and change parameter **-Xmx4g**, set the value depending on how much RAM
3. Execute ```$ docker-compose up -d```
4. Change jenkins directory permissions ```$ chmod 777 jenkins```

**Ready!** Go to https://your-domain.ru and install jenkins
