FROM alpine-java:11.0.9
CMD mkdir  -p /apps/sample-banking-service
ARG JAR_FILE
COPY target/${JAR_FILE} sample-banking-service.jar
CMD  java $JAVA_OPTS -jar sample-banking-service.jar
EXPOSE 9086
