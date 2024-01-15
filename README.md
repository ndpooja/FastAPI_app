# FastAPI App

A simple example for FastAPI application using docker

## 💻 Project setup

Start by cloning or downloading this repository

```bash
git clone https://github.com/ndpooja/FastAPI_app.git
```
## To run the project
Open docker desktop

for building image
```bash
cd FastAPI_app
docker build -t my_fastapi_app .
```

to run the application
```bash
docker run --name mycontainer -p 80:80 my_fastapi_app
```