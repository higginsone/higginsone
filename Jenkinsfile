pipeline {
  agent {
    docker {
      args '-v /home/ubuntu/jenkins_data'
      image 'node:latest'
    }

  }
  stages {
    stage('build') {
      steps {
        sh '''node --version

npm install'''
      }
    }

  }
}