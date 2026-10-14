pipeline {
  agent any
  tools { 
        maven 'Maven_3_8_4'  
    }
   stages{
    stage('CompileandRunSonarAnalysis') {
            steps {	
		sh 'mvn clean verify org.sonarsource.scanner.maven:sonar-maven-plugin:sonar -Dsonar.projectKey=asgbuggywebappafizbappafiz -Dsonar.organization=asgbuggywebappafiz -Dsonar.host.url=https://sonarcloud.io -Dsonar.token=2a7c1d5f44546bb0340ee6b6d77d2bf8a85e47d0'
			}
        } 
  }
}
