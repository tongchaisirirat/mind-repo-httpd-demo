# note

docker build -t httpd_image:latest .

# show image docker
docker images

docker run --name my-service-httpd -d -p 8080:80 httpd_image:latest

# show contrainer runing
docker ps

# show container all
docker ps -a

------------------------------------

docker stop <container-id>

docker rm <your-container-id>

------------------------------------
docker rmi <your-image-id>

# Remove all images at once
docker images -qs
