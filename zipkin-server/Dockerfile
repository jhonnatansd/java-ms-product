FROM openjdk:8
VOLUME /tmp
EXPOSE 9411
ADD ./zipkin-server-2.21.0-exec.jar zipkin-server.jar
ENTRYPOINT ["java", "-jar", "/zipkin-server.jar"]