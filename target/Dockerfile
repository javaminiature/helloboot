FROM alpine:latest
RUN apk --update add openjdk8-jre
COPY helloboot-0.0.1-SNAPSHOT.jar helloboot.jar
CMD ["java", "-jar","helloboot.jar"]