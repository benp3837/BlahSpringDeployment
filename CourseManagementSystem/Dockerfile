#A Dockerfile is used to describe the IMAGE of the application so we can recreate it anywhere

#This image will be based off Amazon's version of Java 11
FROM amazoncorretto:11

#We need to COPY our packaged JAR file from here to our container's storage
COPY target/app.jar app.jar

#The application will be accessible through port 8080
EXPOSE 8080

#Commands to start the actual application
CMD ["java", "-jar", "app.jar"]