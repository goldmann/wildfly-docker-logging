## Build:

    docker build --rm --tag wildfly-syslog .

## Run:

    docker run -d --link syslog:syslog wildfly-syslog
