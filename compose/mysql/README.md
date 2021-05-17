# Para criar servidor Mysql :inbox_tray:



## Baixando a imagem
```
docker pull mysql
```

## Criando container

```
docker run --name <nome container> -e MYSQL_ROOT_PASSWORD=root -d mysql:latest
```

## Logs
```
docker logs <nome container>
```

## Mapeamento de portas
```
docker run --name dev-mysql -e MYSQL_ROOT_PASSWORD=root -d -p 3306:3306 mysql
```

## Via docker-compose

```
docker-compose up -d --build
```

