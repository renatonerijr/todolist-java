


# Como rodar o projeto
```
mvn spring-boot:run
```


# Endpoints

## Endpoint de criar usuários
```
[POST] http://localhost:8080/users
```

Body
```
{
	"name": "Your name",
	"username": "yourusername",
	"password": "123"
}
```

## Endpoint de criar tasks
```
[POST] http://localhost:8080/tasks
```

Body
```
{
	"description": "Tarefa para criar gravar aula",
	"title": "Gravação de daula",
	"priority": "Alta",
	"startAt": "2023-10-15T23:59:59",
	"endAt": "2023-10-15T23:59:59"
}
```

Basic Authorization
```
user: your username
password: your password
```

## Endpoint de atualizar tasks
```
[PUT] http://localhost:8080/tasks/<ID>
```

Body
```
{
	"description": "Tarefa para atualizar gravar aula",
	"title": "Gravação de daula",
	"priority": "Alta",
	"startAt": "2023-10-15T23:59:59",
	"endAt": "2023-10-15T23:59:59"
}
```

Basic Authorization
```
user: your username
password: your password
```