pipeline {
  agent {
    docker {
      image 'maven:3.9.5-amazoncorretto-17'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'mvn clean compile'
      }
    }

  }
}