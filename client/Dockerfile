FROM openjdk:8-jre-alpine
EXPOSE 6884
ADD /target/oauth2-client-1.3.1.jar server.jar
CMD ["/bin/sh","-c","java -Dlight-4j-config-dir=/config -Dlogback.configurationFile=/config/logback.xml -jar /server.jar"]