FROM eclipse-temurin:21
LABEL authors="AgniaEndie"

WORKDIR /minecraft
COPY ./minecraft-server.jar /minecraft
COPY ./eula.txt /minecraft
COPY ./libraries /minecraft/libraries

ENTRYPOINT ["java","-Xms4G","-Xmx8G" ,"-jar","minecraft-server.jar"]