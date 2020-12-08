FROM tomcat:9.0
RUN apt-get update && apt-get install maven git -y
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello
WORKDIR /usr/local/tomcat/boxfuse-sample-java-war-hello
RUN mvn package