pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build completed'
        timeout(time: 5, unit: 'SECONDS') {
              sh 'sleep 2'
          }
      }
    }
    stage('Test') {
      steps {
        echo 'testing completed'
      }
    }
    stage('Deploy') {
      steps {
        echo 'deployment completed'
      }
    }

  }
} 