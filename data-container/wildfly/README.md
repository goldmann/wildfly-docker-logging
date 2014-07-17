## Build

    docker build --rm --tag=wildfly-logs .

## Run

    docker run -d -h wildfly-01 --name wildfly-01 --volumes-from data wildfly-logs
    docker run -d -h wildfly-02 --name wildfly-02 --volumes-from data wildfly-logs

