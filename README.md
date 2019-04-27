# docker-cat

Dockerfile source code repository: https://github.com/cloud-ready/cat

Docker image is built automatically by travis-ci: https://travis-ci.org/cloud-ready/cat


```bash
git clone https://github.com/cloud-ready/docker-mysql.git
cd docker-mysql
docker-compose pull && docker-compose up -d
# For phpMyAdmin open http://localhost:8306 (default root password is root_pass)

cd ..

git clone https://github.com/cloud-ready/docker-cat.git
cd docker-cat
docker-compose pull && docker-compose up -d

# For CAT open http://localhost:8080
```
