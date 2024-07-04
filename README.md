c 78
Временные таблицы

docker login
docker run --name some-mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql
docker ps
docker container list
docker stop some-mysql
docker start some-mysql
docker exec -it some-mysql bash
mysql -u root -p