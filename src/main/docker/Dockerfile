
FROM adoptopenjdk:11-jre-hotspot
MAINTAINER Pavel Voytovitskiy <paulv2007@yandex.ru>

ARG JAR_FILE=*.jar
COPY ${JAR_FILE} application.jar

ENTRYPOINT ["java", "-jar", "application.jar"]