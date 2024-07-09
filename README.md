# flaskr
Flask tutorial with some extras

## How to run
Initialize the database
```
flask --app app init-db
```
Run the application
```
flask --app app run --debug
```
Visit http://127.0.0.1:5000/hello to see the simplest endpoint
Or http://127.0.0.1:5000 to see full blog application built in the tutorial

## How to test
```
pytest
```

## Code coverage
```
coverage run -m pytest
```
