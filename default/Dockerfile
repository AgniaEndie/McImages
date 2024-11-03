FROM eclipse-temurin:21
LABEL authors="AgniaEndie"

# Set the working directory
WORKDIR /minecraft

# Copy necessary files into the container
COPY minecraft-server.jar /minecraft
COPY eula.txt /minecraft
COPY libraries/ /minecraft/libraries/
COPY server.properties /minecraft
COPY ops.json /minecraft

# Set the entry point for the container
ENTRYPOINT ["java", "-Xms4G", "-Xmx8G", "-jar", "minecraft-server.jar", "nogui"]