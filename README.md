# spring-boot-hazelcast-session-sample
## Build & run
### Open shell
`mvn clean package`

`mvn spring-boot:run`

server.port=0 application.properties file will assign HTTP port dynamically
after started successfully search for port at the end of log output on std out

### Open 2nd shell
`mvn spring-boot:run`

after successful start of 2nd shell search for port at the end of log output on std out

## Open browser with two tabs each pointing to 
* http://localhost:port-of-1st-instance
* http://localhost:port-of-2nd-instance
