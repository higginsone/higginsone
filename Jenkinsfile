pipeline {
  agent {
    docker {
      image 'node'
      args '-v /home/ubuntu/jenkins_data'
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