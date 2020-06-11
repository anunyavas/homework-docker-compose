# build
FROM maven:3-jdk-11
COPY . ./
WORKDIR boxfuse-sample-java-war-hello
RUN mvn package
CMD ["cp", "target/hello-1.0.war", "/artifacts"]
