FROM adoptopenjdk:11-jre-hotspot
VOLUME /tmp
WORKDIR /app
ARG JAR_NAME=example-java-app-0.0.1-snapshot.jar
COPY ./build/libs/$JAR_NAME /app
ENV SPRING_OUTPUT_ANSI_ENABLED="ALWAYS"
ENV JHIPSTER_SLEEP="0"
CMD ["java","-jar","/app/*.jar"]