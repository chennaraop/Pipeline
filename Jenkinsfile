pipeline {
  agent {
    node {
      label '17.82.205.138'
    }
    
  }
  stages {
    stage('Intermediate') {
      steps {
        sh '''ifconfig 
hostname
'''
      }
    }
  }
}