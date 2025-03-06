
# Run Flask Application on debian

## Step 1 - Install python3
```bash
sudo apt install python3
```
## Step 2 - Install flask
```bash
pip install flask
```
## Step 3 - Run flask application
```bash
python3 flask-app.py
```
## Test the result:
```bash
curl http://127.0.0.1:5001
```
or
```bash
curl localhost:5001
```
# Run Flask Application on Docker

[Install docker on your system](https://docs.docker.com/engine/install/)

## Step 3: confirm docker status using below command
```bash
sudo systemctl status docker
```
## use below if docker is inactive
```bash
sudo service docker start
```
## Build the docker image
```bash
sudo docker build -t shreya221998/flask-app:latest . 
```

## Run the docker image
```bash
sudo docker run -d shreya221998/flask-app:latest
```
## Enter inside flask-qpp container
```bash
sudo docker exec -itd 1115b285d2a1 bin/bash
```
