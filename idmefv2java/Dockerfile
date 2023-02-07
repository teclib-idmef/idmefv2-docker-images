FROM gradle:7.6-jdk11-jammy

LABEL description="Docker image containing IDMEFV2 Java libraries (format and transport). \
Provides: \
- idmefv2-java-library: IDMEFV2 format library \
- idmefv2-java-transport-library: IDMEFV2 transport library \
- client.sh: shell script to launch a IDMEFV2 test client \
- server.sh: shell script to launch a IDMEFV2 test server \
 "

WORKDIR /idmefv2

RUN git clone https://github.com/teclib-idmef/java-idmef-transport-library.git ; cd java-idmef-transport-library ; ./gradlew build

WORKDIR /idmefv2/java-idmef-transport-library
