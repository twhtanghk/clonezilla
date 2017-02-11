# Clonezilla

Docker image to restore/backup device (e.g. raspberry pi SD/USB Drive) by clonezilla

Up container
============
```
git clone https://github.com/twhtanghk/clonezilla
docker-compose -f clonezilla/docker-compose.yml up -d
```

Start clonezilla
================
Default image path ./data:/home/partimg
```
docker exec -it clonezilla_clone_1 clonezilla
```
