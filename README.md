# Spring Boot Weather WebApp
Docker image
```
docker build -t spectrum/spring-boot-weather-webapp .
docker run --detach --name spring-boot-weather-webapp -p 5000:8080 spectrum/spring-boot-weather-webapp
```

API-endpoint test
```
curl -s http://localhost:5000/api/weather/now/Belgium/Bilzen | jq .
```

Test application: [http://localhost:5000/](http://localhost:5000/)