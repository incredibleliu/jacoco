https://www.petrikainulainen.net/programming/maven/creating-code-coverage-reports-for-unit-and-integration-tests-with-the-jacoco-maven-plugin/


mvn clean test jacoco:report
mvn jacoco:prepare-agent

mvn clean install
mvn sonar:sonar