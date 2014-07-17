FROM jboss/wildfly
RUN sed -i 's|<file relative-to="jboss.server.log.dir" path="server.log"/>|\<file relative-to="jboss.home.dir" path="logs/\${jboss.host.name}/server.log"/\>|' /opt/wildfly/standalone/configuration/standalone.xml

