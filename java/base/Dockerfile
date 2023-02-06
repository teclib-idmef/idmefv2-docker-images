FROM gradle:7.6-jdk11-jammy

WORKDIR /idmefv2

RUN git clone https://github.com/teclib-idmef/java-idmef-transport-library.git

RUN cd /idmefv2/java-idmef-transport-library && ./gradlew build
