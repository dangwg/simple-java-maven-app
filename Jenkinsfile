pipeline {
  agent any
  stages {
    stage('build_test') {
      steps {
        git 'https://github.com/jenkins-docs/simple-java-maven-app.git'
      }
    }

  }
  environment {
    name = 'Goal'
  }
}