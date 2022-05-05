FROM openjdk:11-jre
ADD 0/scala-library-2.13.8.jar 1/scopt_2.13-4.0.1.jar /app/
ADD 2/docker-scopt_2.13-0.1.0-SNAPSHOT.jar /app/docker-scopt_2.13-0.1.0-SNAPSHOT.jar
ENTRYPOINT ["java", "-cp", "\/app\/scala-library-2.13.8.jar:\/app\/scopt_2.13-4.0.1.jar:\/app\/docker-scopt_2.13-0.1.0-SNAPSHOT.jar", "Main"]