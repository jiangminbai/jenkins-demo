pipeline {
  agent {
    docker {
      image 'ubuntu'
    }
  }
  
  stages {
    stage('test') {
      steps {
        sh 'echo hello world'
      }
    }
  }
}