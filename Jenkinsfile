pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('test') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}