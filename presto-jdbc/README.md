docker run  -it --mount type=bind,source="$(pwd)",target=/root/folder --rm openjdk:8-jdk /bin/bash
./mvnw install -pl presto-jdbc -DskipTests
