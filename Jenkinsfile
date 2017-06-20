pipeline {
  agent any
  stages {
    stage('build1') {
      steps {
        sh 'sh ./build1'
      }
    }
    stage('unittest1') {
      steps {
        sh 'sh ./unittest1'
      }
    }
    stage('integration1') {
      steps {
        sh 'sh ./integration1'
      }
    }
    stage('systemTest') {
      steps {
        sh 'sh ./systemTest'
      }
    }
  }
}