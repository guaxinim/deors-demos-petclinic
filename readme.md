# deors-demos-petclinic

The popular Spring Pet Clinic application, updated to work with Tomcat 7 and Spring 3,
with an example of a multi-browser Selenium integration test, and with exemplar Maven
configuration: deployment to OpenShift and Heroku, test coverage per test with SonarQube
and JaCoCo, integration test with Selenium, integration test coverage with JaCoCo,
mutation testing with Pitest and SonarQube and load tests with JMeter.

# execution

mvn clean verify -P cargo-tomcat,selenium-tests,jmeter-tests,pitest-tests  

mvn sonar:sonar -Dsonar.host.url=http://localhost:9000  
