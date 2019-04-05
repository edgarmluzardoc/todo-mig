# todo-mig
Example API for "todos" using node js

## How to run
Run the following commands inside this repo:
- `npm install`
- `npm run start`
- Note that this project will run by defaul on port `5000`

## Test endpoints

Use the example Postman collection in: https://github.com/edgarmluzardoc/todo-mig/blob/master/Todos.postman_collection.json

| Description | Method | Endpoint | Headers | Body |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Get all todos | GET| http://localhost:5000/api/v1/todos |  |  |
| Get a single todo | GET| http://localhost:5000/api/v1/todos/1 |  |  |
| Create a todo | POST| http://localhost:5000/api/v1/todos | (*) | (**) |
| Update a todo | PUT| http://localhost:5000/api/v1/todos/1 | (*) | (**) |
| Delete a single todo | DEL| http://localhost:5000/api/v1/todos/2 |  |  |

(*)  ```Content-Type: application/x-www-form-urlencoded```

(**) ```title: any-title, description: any-description```
