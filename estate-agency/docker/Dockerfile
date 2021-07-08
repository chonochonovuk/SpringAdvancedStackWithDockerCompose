# we will use openjdk 8 with alpine as it is a very small linux distro
FROM adoptopenjdk/openjdk14-openj9:x86_64-alpine-jre-14.0.2_12_openj9-0.21.0

# copy the packaged jar file into our docker image
COPY estate-agency-0.0.1-SNAPSHOT.jar /demo.jar
 
# set the startup command to execute the jar
CMD ["java", "-jar", "/demo.jar"]

EXPOSE 8080
