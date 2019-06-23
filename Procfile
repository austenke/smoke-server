web: java $JAVA_OPTS -jar target/App-1.0-SNAPSHOT.jar db migrate service.yml && java $JAVA_OPTS -Ddw.server.applicationConnectors[0].port=$PORT -jar target/App-1.0-SNAPSHOT.jar server service.yml
