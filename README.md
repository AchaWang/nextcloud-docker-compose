# nextcloud-docker-compose
### nextcloud server by docker-compose , with letsencrypt ssl
### this is a fork from (https://github.com/nextcloud/docker/tree/master/.examples/docker-compose/with-nginx-proxy)


### **1.open docker-compose.yml
#### *(1)  insert your nextcloud domain behind VIRTUAL_HOST=and LETSENCRYPT_HOST=
#### *(2)  enter a valid email behind LETSENCRYPT_EMAIL=
#### *(3)  if you use mariadb or mysql choose a root password for the database behind MYSQL_ROOT_PASSWORD=
### **2.choose a password for the database user nextcloud in db.env behind MYSQL_PASSWORD= (for mariadb/mysql) or POSTGRES_PASSWORD= (for postgres)
### **3.run docker-compose build --pull to pull the most recent base images and build the custom dockerfiles
####**4.start nextcloud with docker-compose up -d
### **If you want to update your installation to a newer version of nextcloud, repeat the steps 3 and 4
