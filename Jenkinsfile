pipeline {
  agent {
    docker {
      image 'kirubatvm/ubuntuimagesrepo:1.0'
    }

  }
  stages {
    stage('stage1') {
      steps {
        sh 'apt-get update -y'
      }
    }
  }
}