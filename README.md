# Workshop python flask

```
pip install -r requirements.txt
python app.py
```


## Run with docker
```
$docker image build -t demo-python:1.0 .
$docker container run -d -p 5000:5000 demo-python:1.0
$curl http://localhost:5000
```

## Run with docker compose
```
$docker-compose build
$docker-compose up -d
$docker-compose ps
$curl http://localhost:5555
```
