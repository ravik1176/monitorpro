# monitorpro

## Dependencies Required and needed to add in pom.xml for Spring Project.
1. spring-boot-starter-actuator
   ```
   	<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-actuator</artifactId>
		</dependency>
   ```

2. micrometer-registry-prometheus
   ```
   	<dependency>
			<groupId>io.micrometer</groupId>
			<artifactId>micrometer-registry-prometheus</artifactId>
			<scope>runtime</scope>
		</dependency>
   ```

## Prerequisites
1. JDK 11 / JRE 11
2. Maven
3. IDE (VSCODE/ ECLIPSE) - Optional

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
