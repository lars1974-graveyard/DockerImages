FROM jboss/wildfly:9.0.0.Final

ADD module.xml /opt/jboss/wildfly/modules/com/mysql/main/
ADD sqljdbc42.jar /opt/jboss/wildfly/modules/com/mysql/main/
ADD vaadin-client-7.5.4.jar /opt/jboss/wildfly/modules/com/mysql/main/
ADD vaadin-client-compiled-7.5.4.jar /opt/jboss/wildfly/modules/com/mysql/main/
ADD vaadin-server-7.5.4.jar /opt/jboss/wildfly/modules/com/mysql/main/
ADD vaadin-sass-compiler-0.9.12.jar /opt/jboss/wildfly/modules/com/mysql/main/
ADD vaadin-shared-7.5.4.jar /opt/jboss/wildfly/modules/com/mysql/main/
ADD vaadin-themes-7.5.4.jar /opt/jboss/wildfly/modules/com/mysql/main/

ADD deltaspike-core-api-1.4.1.jar /opt/jboss/wildfly/modules/com/mysql/main/
ADD deltaspike-core-impl-1.4.1.jar /opt/jboss/wildfly/modules/com/mysql/main/
ADD flute-1.3.0.gg2.jar /opt/jboss/wildfly/modules/com/mysql/main/
ADD guava-16.0.1.vaadin1.jar /opt/jboss/wildfly/modules/com/mysql/main/
ADD jsoup-1.8.1.jar /opt/jboss/wildfly/modules/com/mysql/main/
ADD sac-1.3.jar /opt/jboss/wildfly/modules/com/mysql/main/
ADD streamhtmlparser-jsilver-0.0.10.vaadin1.jar /opt/jboss/wildfly/modules/com/mysql/main/

EXPOSE 8080 9990