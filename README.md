# microblog
Micro Website using Python Flask

Run Server
```
flask run
```

Creating The Migration Repository
```
flask db init
```

The First Database Migration
```
flask db migrate -m "users table"
```

Database Downgrade Upgrade
```
flask db downgrade
flask db upgrade
```