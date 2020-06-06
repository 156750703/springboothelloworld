FROM 192.168.137.49:5000/jre8
VOLUME /tmp
ADD helloworld.jar app.jar
RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
