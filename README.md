# Docker Nginx

#Build Dockerfile:

docker build -t nginx .

#Run Docker:

docker run --name nginx -d  -p 4567:80 nginx
