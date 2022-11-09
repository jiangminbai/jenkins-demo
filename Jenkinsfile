pipeline {
  agent any
  
  stages {
    stage('stage 1') {
      steps {
        echo 'install dependencies'
      }
    }
    stage('stage 2') {
      steps {
        echo 'yarn build'
      }
    }
    stage('stage 3') {
      steps {
        echo 'make Images'
      }
    }
    stage('stage 4') {
      steps {
        echo 'deploy Images'
      }
    }
  }
}