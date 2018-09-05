https://www.petrikainulainen.net/programming/maven/creating-code-coverage-reports-for-unit-and-integration-tests-with-the-jacoco-maven-plugin/


mvn clean test jacoco:report
mvn clean install
mvn jacoco:prepare-agent
mvn sonar:sonar


mvn clean org.jacoco:jacoco-maven-plugin:prepare-agent install
    clean org.jacoco:jacoco-maven-plugin:prepare-agent install -Dmaven.test.failure.ignore=true