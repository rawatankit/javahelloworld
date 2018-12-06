FROM java:8
#LABEL maintainer="Codemiro Technolgies"
LABEL maintainer="Testing"
VOLUME /tmp
EXPOSE 8080
ADD target/demo.jar /demo.jar
RUN bash -c 'touch /bgbs-api.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/demo.jar"]
