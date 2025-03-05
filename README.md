
# Run Flask Application on debian

## Step 1 - Install python3
sudo apt install python3

## Step 2 - Install flask
pip install flask

## Step 3 - Run flask application
python3 flask-app.py

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
sudo systemctl status docker

## use below if docker is inactive
sudo service docker start

