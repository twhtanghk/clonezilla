# Clonezilla

Docker image to restore/backup device (e.g. raspberry pi SD/USB Drive) by clonezilla

Up container
============
```
git clone https://github.com/twhtanghk/clonezilla
docker-compose -f cloneaill/docker-compose.yml up -d
```

Start clonezilla
================
```
docker exec -it clonezilla_clone_1 clonezilla
```
