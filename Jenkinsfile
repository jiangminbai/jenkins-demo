#!/usr/bin/env groovy

pipeline {
  agent {
    docker {
      image 'ubuntu'
    }
  }
  
  stages {
    stage('test') {
      steps {
        echo 'hello world'
      }
    }
  }
}