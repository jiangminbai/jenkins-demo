#!/usr/bin/env groovy

pipeline {
  agent {
    docker {
        image 'node:16.13.1-alpine'
        label 'my-defined-label'
        args  '-v /tmp:/tmp'
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