pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build'
      }
    }

    stage('Dev') {
      steps {
        echo 'Dev'
        sleep 30
      }
    }

    stage('Test') {
      steps {
        echo 'Test'
        sleep 20
      }
    }

    stage('Prod') {
      steps {
        echo 'Prod'
        sleep 30
      }
    }

  }
}