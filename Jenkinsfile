pipeline {
  agent any
  tools {
    maven 'maven-3.6.3' 
  }
  stages {
    stage ('Build') {
      steps {
	git 'https://github.com/Ronitgit/java-spring-boot-maven.git'
        sh 'mvn clean package'
      }
    }
  }
}
