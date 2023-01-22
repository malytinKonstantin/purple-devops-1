docker build -t my/nginx .
docker run -d --name nginx-test my/nginx
docker exec -it nginx-test bash
curl GET localhost:80

![result](image.png)
