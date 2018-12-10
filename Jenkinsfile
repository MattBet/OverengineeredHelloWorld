pipeline {
  agent {
    docker {
      image 'maven'
    }

  }
  stages {
    stage('error') {
      steps {
        echo 'Salut'
        sh 'mvn test'
      }
    }
  }
}