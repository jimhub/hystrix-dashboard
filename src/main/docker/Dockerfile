FROM java:7
VOLUME /tmp
ADD hystrix-dashboard-0.0.1.BUILD-SNAPSHOT.jar /app.jar
RUN bash -c 'touch /app.jar'
EXPOSE 7979
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]