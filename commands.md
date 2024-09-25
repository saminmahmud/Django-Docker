##### Building a Docker Image
```
docker build -t my-docker-image .
```
<br>

##### Running a Docker Container
```
docker run -d --name my-docker-container -p 8000:8000 -v .:/app my-docker-image
```
<br>

##### Running a Docker Container from a Docker Compose file
```
docker compose up -d
```
<br>

##### Build & Running a Docker Container from a Docker Compose file ✅
```
docker-compose up --build -d
```
<br>

##### Stop a Docker Container
```
docker stop my-docker-container
```
<br>

##### Remove a Docker Container
```
docker rm my-docker-container
```

