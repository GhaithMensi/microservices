FROM openjdk:8-jdk-alpine
EXPOSE 8080
ADD /target/zuul-geteway-1.0.0-RELEASE.jar zuul-geteway.jar
ENTRYPOINT ["java", "-jar", "zuul-geteway.jar"]