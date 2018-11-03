# docker-node-mongo

docker-node-mongo

### commands

docker container run -it -p 80:80 nginx

docker container run -d -p 8080:80 --name mynginx nginx

docker container run -d -p 3306:3306 --name mysql --env MYSQL_ROOT_PASSWORD=123456 mysql

docker container exec -it mynginx bash

Bind

docker container run -d -p 8080:80 -v C:\Users\Beast\Desktop\docker-node-mongo-master:/usr/share/nginx/html --name nginx-website nginx

Upload
docker image build -t la102/nginx-website .

Heroku push
heroku container:push web --app dockerleslie

Heroku deploy
heroku container:release web --app dockerleslie
