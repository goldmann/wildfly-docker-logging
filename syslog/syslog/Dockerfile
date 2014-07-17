FROM fedora
RUN yum -y install syslog-ng && yum clean all
ADD syslog-ng.conf /etc/syslog-ng/syslog-ng.conf

VOLUME /var/log/wildfly
EXPOSE 514/udp

CMD ["/usr/sbin/syslog-ng", "-F", "--no-caps"]
