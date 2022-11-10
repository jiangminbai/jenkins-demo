#!/usr/bin/env groovy

pipeline {
  agent any
  
  stages {
    stage('stage dev 1') {
      steps {
        echo 'install dependencies'
      }
    }
    stage('stage dev 2') {
      steps {
        echo 'yarn build'
      }
    }
    stage('stage dev 3') {
      steps {
        echo 'make Images'
      }
    }
    stage('stage dev 4') {
      steps {
        echo 'deploy Images'
      }
    }
  }
}