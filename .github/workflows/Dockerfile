FROM tomcat:8.5.92
COPY /target/sampleapp.war /usr/local/tomcat/webapps
RUN  addgroup -S devsec  && adduser -S devsecops -G devsec
USER 999
EXPOSE 8080
CMD /usr/local/tomcat/bin/catalina.sh run
##
