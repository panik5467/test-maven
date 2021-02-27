# test-maven
Example Using maven profiles

## build
mvn package
java -jar target/project-1.0.jar

## build environnement de test
mvn package -P test

## build environnement de prod
mvn package -P prod
