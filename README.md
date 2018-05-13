# spring-boot-hazelcast-session-sample
## Build & run
### Open shell
`mvn clean package`

`mvn spring-boot:run`

After successful start search for port at the end of log output on std out

server.port=0 application.properties file will assign HTTP port dynamically
`2018-05-13 12:11:49.876  INFO 13516 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 61731 (http) with ...`

### Open 2nd shell
`mvn spring-boot:run`

after successful start of 2nd shell search for port at the end of log output on std out

## Open browser with two tabs each pointing to 
* http://localhost:port-of-1st-instance
* http://localhost:port-of-2nd-instance
