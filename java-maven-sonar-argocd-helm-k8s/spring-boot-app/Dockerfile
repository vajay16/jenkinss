# You can change this base image to anything else
# But make sure to use the correct version of Java
FROM adoptopenjdk/openjdk11:alpine-jre




WORKDIR /opt/app

COPY /var/lib/jenkins/.m2/repository/com/abhishek/spring-boot-demo/1.0/spring-boot-demo-1.0.jar app.jar

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]
