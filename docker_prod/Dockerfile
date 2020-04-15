FROM ubuntu:18.04
RUN apt update && apt install -y git && apt install -y maven
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello myapp
WORKDIR myapp
RUN mvn package

