FROM tomcat:8.0-alpine
ADD boxfuse-sample-java-war-hello/target/hello-1.0.war /usr/local/tomcat/webapps/

EXPOSE 8080

CMD [“catalina.sh”, “run”]
