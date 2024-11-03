FROM eclipse-temurin:21
LABEL authors="AgniaEndie"

WORKDIR /minecraft
COPY ./minecraft-server.jar /minecraft
COPY ./eula.txt /minecraft
COPY ./libraries /minecraft/libraries
COPY ./server.properties /minecraft
COPY ./ops.json /minecraft

ENTRYPOINT ["java","-Xms4G","-Xmx8G" ,"-jar","minecraft-server.jar"]