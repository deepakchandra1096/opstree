FROM centos
RUN apt update
VOLUME /tmp
ADD /Spring3HibernateApp/target/Spring3HibernateApp-1.8-SNAPSHOT Spring3HibernateApp.war
EXPOSE 8080
CMD  java -jar Spring3HibernateApp.war
