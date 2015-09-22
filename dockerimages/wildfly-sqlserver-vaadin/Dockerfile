FROM jboss/wildfly:9.0.0.Final

ADD com/microsoft/sqlserver/jdbc/main/module.xml /opt/jboss/wildfly/modules/com/microsoft/sqlserver/jdbc/main/
ADD com/microsoft/sqlserver/jdbc/main/sqljdbc4.jar /opt/jboss/wildfly/modules/com/microsoft/sqlserver/jdbc/main/
ADD com/vaadin/vaadin-client-7.5.4.jar /opt/jboss/wildfly/modules/com/vaadin/
ADD com/vaadin/vaadin-client-compiled-7.5.4.jar /opt/jboss/wildfly/modules/com/vaadin/
ADD com/vaadin/vaadin-server-7.5.4.jar /opt/jboss/wildfly/modules/com/vaadin/
ADD com/vaadin/vaadin-sass-compiler-0.9.12.jar /opt/jboss/wildfly/modules/com/vaadin/
ADD com/vaadin/vaadin-shared-7.5.4.jar /opt/jboss/wildfly/modules/com/vaadin/
ADD com/vaadin/vaadin-themes-7.5.4.jar /opt/jboss/wildfly/modules/com/vaadin/

ADD com/vaadin/deltaspike-core-api-1.4.1.jar /opt/jboss/wildfly/modules/com/vaadin/
ADD com/vaadin/deltaspike-core-impl-1.4.1.jar /opt/jboss/wildfly/modules/com/vaadin/
ADD com/vaadin/flute-1.3.0.gg2.jar /opt/jboss/wildfly/modules/com/vaadin/
ADD com/vaadin/guava-16.0.1.vaadin1.jar /opt/jboss/wildfly/modules/com/vaadin/
ADD com/vaadin/jsoup-1.8.1.jar /opt/jboss/wildfly/modules/com/vaadin/
ADD com/vaadin/sac-1.3.jar /opt/jboss/wildfly/modules/com/vaadin/
ADD com/vaadin/streamhtmlparser-jsilver-0.0.10.vaadin1.jar /opt/jboss/wildfly/modules/com/vaadin/

EXPOSE 8080 9990