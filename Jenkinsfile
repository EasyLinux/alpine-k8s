pipeline {
  agent any
  stages {
    stage('Image') {
      steps {
        sh 'docker image build -t easylinux/alpine-k8s .'
      }
    }
  }
}