FROM tomcat:8.0
RUN cp  _java-deploy/drop/target/java-tomcat-maven-example.war  /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
