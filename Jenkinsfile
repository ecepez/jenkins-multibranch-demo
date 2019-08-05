pipeline {
  agent any
  stages {
    stage('Build It all!') {
      steps {
        echo 'Building Something Cool!'
        sleep(time: 10, unit: 'MINUTES')
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}
