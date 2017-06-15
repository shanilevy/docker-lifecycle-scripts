FROM yodafrog.sas.jfrog.internal:5002/docker-webinar-framework:latest

MAINTAINER Jonathan ROQUELAURE jonathanr@jfrog.com

ADD war/*.war /home/exec/tomcat/webapps/swampup.war

CMD /bin/bash -c cd /home/exec; /home/exec/tomcat/bin/catalina.sh run
