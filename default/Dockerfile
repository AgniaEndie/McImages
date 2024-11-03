FROM eclipse-temurin:21
LABEL authors="AgniaEndie"

WORKDIR /tmp
COPY ./minecraft-server.jar /tmp
COPY ./eula.txt /tmp

ENTRYPOINT ["java","-Xms4G","-Xmx8G" ,"-jar","minecraft-server.jar"]