FROM eclipse-temurin:21
LABEL authors="AgniaEndie"

WORKDIR /minecraft
COPY ./minecraft-server.jar /
COPY ./eula.txt /
COPY ./libraries /libraries
COPY ./server.properties /
COPY ./ops.json /

ENTRYPOINT ["java","-Xms4G","-Xmx8G" ,"-jar","minecraft-server.jar"]