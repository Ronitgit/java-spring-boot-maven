pipeline {
    agent any
      stages {
        stage('log version info') {
      steps {
     git 'https://github.com/Ronitgit/java-spring-boot-maven.git'
        sh 'mvn --version'
        sh 'mvn clean install'
      }
    }
  }
}
