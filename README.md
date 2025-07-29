./mvnw spring-boot:run

curl http://localhost:808

http://localhost:8080

curl http://localhost:8080/actuator/health

http://localhost:8080/hello

http://localhost:8080/hello?name=Amy

Remove-item alias:curl 

curl -X POST http://localhost:8080/actuator/shutdown
