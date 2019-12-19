pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        withMaven(jdk: 'JDK8', maven: 'M3', mavenLocalRepo: '~/.M2/') {
          sh 'mvn clean'
        }

      }
    }

  }
}