# monitorpro


## Buildiing steps

1. Build
```
# mvn clean package
```

2. Run the jar
```
# java -jar target/<artifact>.jar
```

3. Access the app

   App: http://localhost:8080/
   Health: http://localhost:8080/actuator/health
   Prometheus: http://localhost:8080/actuator/prometheus

# Thanks 