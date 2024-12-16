# To-Do List API in Python Flask

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

## About the tutorial

In this project, we are going to be building a REST API that exposes 3 endpoints to the internet:

```txt
GET /todos
POST /todos
DELETE /todos/<int:position>
```

### GET /todos

Will return the list of all todos like this:

```javascript
[
  {
    done: true,
    label: "Sample Todo 1",
  },
  {
    done: true,
    label: "Sample Todo 2",
  },
];
```

### POST /todos

This will add a new todo to the list with the following request body:

```javascript
{
    "done": true,
    "label": "Sample Todo 1"
}
```

And return the updated list of todos.

### DELETE /todos/<int:position>

This will remove one todo, based on a given position in the todos list, at the end of the URL and return the updated list of todos.

## Sources:

This exercise is part of the complete 4Geeks Academy Full Stack course:

[![4Geeks Academy](https://img.shields.io/badge/4Geeks%20Academy-blue.svg)](https://4geeks.com/syllabus/santiago-pt-49/project/python-flask-api-tutorial)
