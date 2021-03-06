# user_management_system
User management system - Flask Mongo Db ORM
## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/udhayukgit/flask_crud_mongo.git
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ python3 -m venv env
$ source env/bin/activate
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `venv`.

Once `pip` has finished downloading the dependencies:

Used Cloud Mongo db
-------------------

```sh
Database -  usermanagement 
```

To Run

```sh
(env)$ gunicorn --bind 0.0.0.0:8000 wsgi:app
```

And navigate to 
```sh
`http://127.0.0.1:8000/`.
```
with pagination -  e.g 

```sh
`http://127.0.0.1:8000/?page=1&limit=2`
```

Postman Collection link 
```sh
`https://www.getpostman.com/collections/cf2c0b6e12c1e4d92f24`
```

You can then import this link into Postman 

```sh
("Import -> Link")
```

Run Test case file

```sh
(env)$ python test_case.py
```
