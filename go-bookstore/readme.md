# Golang With MySQL Book Management System

Run mariadb for SQL

```
docker run -d --name mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=secret -v ~/local-devs/mysql:/var/lib/mysql mariadb:10.5.8
```

Endpoints
```
Index   localhost:9010/book/
Show    localhost:9010/book/{id}
Create  localhost:9010/book/
Update  localhost:9010/book/{id}
Delete  localhost:9010/book/{id}
```