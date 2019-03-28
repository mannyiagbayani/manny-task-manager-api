TASK MANAGER APP
An API to create / delete / update task integrated with authentication. 

NPM packages
- @sendgrid/mail
- bcryptjs
- express
- jsonwebtoken
- mongodb
- mongoose
- multer
- sharp
- validator

- create user endpoint
```
//POST
https://manny-task-manager-api.herokuapp.com/users
```
- create user payload

```
{
	"name":"User 1",
	"age": 20,
	"email":"user1@example.com",
	"password": "user1-pa$sword"
}
```

- login user endpoint
```
//POST
https://manny-task-manager-api.herokuapp.com/users
```
- login user payload

```
{
	"email":"user1@example.com",
	"password": "user1-pa$sword"
}
```
- read user endpoint
```
//GET
https://manny-task-manager-api.herokuapp.com/users/me
```
- create user task endpoint
```
//POST
https://manny-task-manager-api.herokuapp.com/tasks
```
- create task payload

```
{
	"description": "buy lotto tickets",
	"completed" : false
}
```

- read user task endpoint
```
//GET
https://manny-task-manager-api.herokuapp.com/tasks?sortBy=createdAt:asc
```
