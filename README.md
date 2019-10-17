### Install package
```
$ sudo pip3 install flask-bcrypt
$ sudo pip3 install flask-restplus
$ sudo pip3 install Flask-Migrate
$ sudo pip3 install pyjwt
$ sudo pip3 install Flask-Script
$ sudo pip3 install flask_testing
```

### Create DB information
```
$ python3 manage.py db init
$ python3 manage.py db migrate --message 'initial database migration'
$ python3 manage.py db upgrade
```

### Run
```
$ python3 manage.py run
```

### Test
```
$ python3 manage.py test
```

### Reference
[How to structure a Flask-RESTPlus web service for production builds](https://www.freecodecamp.org/news/structuring-a-flask-restplus-web-service-for-production-builds-c2ec676de563/)
